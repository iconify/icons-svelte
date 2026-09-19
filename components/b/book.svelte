<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbhxcpbvt.css';
import '../../css/h/hd8ss2bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vbhxcpbvt"/><path class="hd8ss2bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:book" {...props}></Icon>
