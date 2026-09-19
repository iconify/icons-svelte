<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khk__8bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="khk__8bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:open-with-mirrored" {...props}></Icon>
