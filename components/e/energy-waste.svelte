<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tici9vb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tici9vb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:energy-waste" {...props}></Icon>
