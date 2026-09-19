<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly82mzboj.css';
import '../../css/x/xxtpbdb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ly82mzboj"/><path class="xxtpbdb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pedestrian" {...props}></Icon>
