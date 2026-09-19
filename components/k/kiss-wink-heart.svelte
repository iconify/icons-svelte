<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrk10cbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":512};
const content = `<path class="xrk10cbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:kiss-wink-heart" {...props}></Icon>
