<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4t-l8b1f.css';
import '../../css/e/ew86px5aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4t-l8b1f"/><path class="ew86px5aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:diagram" {...props}></Icon>
