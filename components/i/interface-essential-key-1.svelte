<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6dzgw0rm.css';
import '../../css/n/n--stkfmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b6dzgw0rm"/><path class="n--stkfmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-key-1" {...props}></Icon>
