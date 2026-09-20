<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqy2yo0ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqy2yo0ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:longhorn" {...props}></Icon>
