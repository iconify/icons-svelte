<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctgdt-6yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ctgdt-6yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-stipple" {...props}></Icon>
