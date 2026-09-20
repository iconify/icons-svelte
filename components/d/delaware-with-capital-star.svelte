<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiaghib3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iiaghib3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:delaware-with-capital-star" {...props}></Icon>
