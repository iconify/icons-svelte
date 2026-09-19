<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbb7ehn3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gbb7ehn3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flood" {...props}></Icon>
