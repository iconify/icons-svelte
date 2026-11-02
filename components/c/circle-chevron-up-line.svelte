<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruo8un5iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruo8un5iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-chevron-up-line" {...props}></Icon>
