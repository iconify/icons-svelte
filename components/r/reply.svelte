<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz1f_7svg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uz1f_7svg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:reply" {...props}></Icon>
