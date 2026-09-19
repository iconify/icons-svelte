<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz0f-ub_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rz0f-ub_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:device-run" {...props}></Icon>
