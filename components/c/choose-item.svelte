<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p619a9b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p619a9b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:choose-item" {...props}></Icon>
