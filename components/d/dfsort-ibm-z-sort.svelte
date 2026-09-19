<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5djkcoxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c5djkcoxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dfsort-ibm-z-sort" {...props}></Icon>
