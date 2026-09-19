<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbr2puogx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="xbr2puogx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:fullscreen" {...props}></Icon>
