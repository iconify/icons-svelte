<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-9s02ozz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t-9s02ozz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-rolling-eyes" {...props}></Icon>
