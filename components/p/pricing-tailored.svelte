<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8er1hxdx.css';
import '../../css/a/a3f5iab8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y8er1hxdx"/><path class="a3f5iab8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pricing-tailored" {...props}></Icon>
