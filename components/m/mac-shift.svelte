<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xle_b1dlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xle_b1dlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mac-shift" {...props}></Icon>
