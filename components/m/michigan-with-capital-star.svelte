<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dar1jw_ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dar1jw_ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:michigan-with-capital-star" {...props}></Icon>
