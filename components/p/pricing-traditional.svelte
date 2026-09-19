<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez9s18yps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ez9s18yps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pricing-traditional" {...props}></Icon>
