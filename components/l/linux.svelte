<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb3q0tz5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sb3q0tz5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:linux" {...props}></Icon>
