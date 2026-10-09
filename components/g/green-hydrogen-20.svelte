<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igszs0yyx.css';
import '../../css/r/r_cx60bme.css';
import '../../css/d/dvybr6c4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="igszs0yyx"/><path class="r_cx60bme"/><path class="dvybr6c4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-hydrogen-20" {...props}></Icon>
