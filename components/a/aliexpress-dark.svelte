<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b09u8ms8j.css';
import '../../css/x/xyyx10_gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b09u8ms8j"/><path class="xyyx10_gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliexpress-dark" {...props}></Icon>
