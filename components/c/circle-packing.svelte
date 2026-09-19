<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6-affb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6-affb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-packing" {...props}></Icon>
