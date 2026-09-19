<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3nv8zlly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w3nv8zlly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:at" {...props}></Icon>
