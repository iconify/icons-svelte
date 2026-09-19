<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zddhfu_7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zddhfu_7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-tt" {...props}></Icon>
