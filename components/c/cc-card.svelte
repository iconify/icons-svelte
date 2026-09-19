<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0nttob5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2368,"height":1664};
const content = `<path class="m0nttob5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:cc-card" {...props}></Icon>
