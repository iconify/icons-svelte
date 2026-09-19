<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3frg7bxu.css';
import '../../css/y/yr77b-b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w3frg7bxu"/><path class="yr77b-b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delivery-add" {...props}></Icon>
