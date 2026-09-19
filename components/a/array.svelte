<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r69d1vbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r69d1vbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array" {...props}></Icon>
