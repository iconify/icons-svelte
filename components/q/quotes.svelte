<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg1wa1tlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rg1wa1tlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:quotes" {...props}></Icon>
