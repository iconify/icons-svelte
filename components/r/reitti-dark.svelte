<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdt8x3_lk.css';
import '../../css/y/yurfh5b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kdt8x3_lk"/><path class="yurfh5b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reitti-dark" {...props}></Icon>
