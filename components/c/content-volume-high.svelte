<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o00hksstx.css';
import '../../css/a/a_r59m-6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o00hksstx"/><path class="a_r59m-6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-volume-high" {...props}></Icon>
