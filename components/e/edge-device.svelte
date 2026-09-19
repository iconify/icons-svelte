<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czq8nj3ot.css';
import '../../css/t/t-nlx2bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="czq8nj3ot"/><path class="t-nlx2bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edge-device" {...props}></Icon>
