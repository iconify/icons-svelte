<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aus8_o7lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aus8_o7lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-bullet" {...props}></Icon>
