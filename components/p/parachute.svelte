<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyiav2-py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xyiav2-py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:parachute" {...props}></Icon>
