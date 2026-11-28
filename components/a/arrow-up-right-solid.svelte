<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxmzjib8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxmzjib8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-right-solid" {...props}></Icon>
