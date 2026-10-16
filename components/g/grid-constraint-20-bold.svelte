<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6bewdbru.css';
import '../../css/l/lm0-7bbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6bewdbru"/><path class="lm0-7bbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-constraint-20-bold" {...props}></Icon>
