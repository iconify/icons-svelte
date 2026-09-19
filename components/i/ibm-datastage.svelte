<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3kq37bng.css';
import '../../css/x/xqe6h1fjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i3kq37bng"/><path class="xqe6h1fjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-datastage" {...props}></Icon>
