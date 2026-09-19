<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-g782bfv.css';
import '../../css/z/z8g5xoj5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-g782bfv"/><path class="z8g5xoj5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail-unread" {...props}></Icon>
