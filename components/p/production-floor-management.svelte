<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl7ibtbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rl7ibtbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:production-floor-management" {...props}></Icon>
