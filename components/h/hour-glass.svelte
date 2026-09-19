<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0bbvfb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w0bbvfb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hour-glass" {...props}></Icon>
