<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf8q1q14h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zf8q1q14h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:language" {...props}></Icon>
