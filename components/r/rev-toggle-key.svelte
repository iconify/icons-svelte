<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyo3w6x8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uyo3w6x8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rev-toggle-key" {...props}></Icon>
