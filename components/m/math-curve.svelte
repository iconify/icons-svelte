<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuxfbccad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kuxfbccad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:math-curve" {...props}></Icon>
