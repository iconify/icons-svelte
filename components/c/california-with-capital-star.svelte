<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdi6qtbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cdi6qtbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:california-with-capital-star" {...props}></Icon>
