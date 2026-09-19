<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meej0ibwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="meej0ibwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:doc" {...props}></Icon>
