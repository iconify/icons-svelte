<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-hw09zhx.css';
import '../../css/b/bbzizl2ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c-hw09zhx"/><path class="bbzizl2ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-microphone" {...props}></Icon>
