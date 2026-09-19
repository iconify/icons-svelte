<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgv6f4bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mgv6f4bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cube" {...props}></Icon>
