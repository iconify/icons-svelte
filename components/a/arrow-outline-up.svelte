<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymp_cgxhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ymp_cgxhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-outline-up" {...props}></Icon>
