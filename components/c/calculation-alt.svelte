<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji2bvvmog.css';
import '../../css/c/ctgububiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ji2bvvmog"/><path class="ctgububiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calculation-alt" {...props}></Icon>
