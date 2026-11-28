<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cstoc4c1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cstoc4c1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brackets-solid" {...props}></Icon>
