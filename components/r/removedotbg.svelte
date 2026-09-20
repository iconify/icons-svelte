<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_5nxcc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_5nxcc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:removedotbg" {...props}></Icon>
