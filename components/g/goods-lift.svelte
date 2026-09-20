<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew34l9b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ew34l9b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:goods-lift" {...props}></Icon>
