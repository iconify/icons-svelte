<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgfy-nl4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgfy-nl4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pivot-vertical" {...props}></Icon>
