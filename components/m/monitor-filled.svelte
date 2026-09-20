<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfb18lbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfb18lbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:monitor-filled" {...props}></Icon>
