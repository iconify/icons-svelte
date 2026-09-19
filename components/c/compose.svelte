<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er92zo0ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="er92zo0ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:compose" {...props}></Icon>
