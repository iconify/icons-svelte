<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz_ni_bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tz_ni_bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:derelict-house" {...props}></Icon>
