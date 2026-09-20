<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf-rtlrxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yf-rtlrxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:forward" {...props}></Icon>
