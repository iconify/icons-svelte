<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf6_e5b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mf6_e5b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carousel-horizontal" {...props}></Icon>
