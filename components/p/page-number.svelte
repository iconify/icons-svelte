<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p41rr2x8b.css';
import '../../css/e/e00g5nbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p41rr2x8b"/><path class="e00g5nbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:page-number" {...props}></Icon>
