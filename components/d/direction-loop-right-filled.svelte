<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrvbtsb1t.css';
import '../../css/x/x5brej6ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrvbtsb1t"/><path class="x5brej6ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-loop-right-filled" {...props}></Icon>
