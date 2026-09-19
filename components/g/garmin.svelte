<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0_0w2ecl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0_0w2ecl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:garmin" {...props}></Icon>
