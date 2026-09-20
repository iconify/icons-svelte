<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhnt1hz_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vhnt1hz_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dumpster-fire-solid" {...props}></Icon>
