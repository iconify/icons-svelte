<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_w6esxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oe_w6esxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:json-reference" {...props}></Icon>
