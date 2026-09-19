<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2yv4rdoa.css';
import '../../css/u/uyf_mbp3e.css';
import '../../css/w/w5qbufbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c2yv4rdoa"/><path class="uyf_mbp3e"/><path class="w5qbufbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hybrid-networking" {...props}></Icon>
