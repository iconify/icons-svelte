<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzqj45pit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pzqj45pit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:border-bottom" {...props}></Icon>
