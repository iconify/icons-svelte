<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsd66bbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qsd66bbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:duble-corner-arrow-5" {...props}></Icon>
