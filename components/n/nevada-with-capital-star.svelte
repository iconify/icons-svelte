<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryemehblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ryemehblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nevada-with-capital-star" {...props}></Icon>
