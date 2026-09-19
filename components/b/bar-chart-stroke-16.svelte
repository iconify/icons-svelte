<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avixlhbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="avixlhbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-stroke-16" {...props}></Icon>
