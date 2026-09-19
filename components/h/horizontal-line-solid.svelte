<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dstqnbcdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dstqnbcdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:horizontal-line-solid" {...props}></Icon>
