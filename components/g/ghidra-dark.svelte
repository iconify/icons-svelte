<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhmw-kb7l.css';
import '../../css/i/i2b0w4dly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhmw-kb7l"/><path class="i2b0w4dly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghidra-dark" {...props}></Icon>
