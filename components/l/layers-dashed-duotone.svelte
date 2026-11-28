<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxgfvg45l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxgfvg45l primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-dashed-duotone" {...props}></Icon>
