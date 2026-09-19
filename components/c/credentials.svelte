<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh9mnbc-e.css';
import '../../css/g/gibdywb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zh9mnbc-e"/><path class="gibdywb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:credentials" {...props}></Icon>
