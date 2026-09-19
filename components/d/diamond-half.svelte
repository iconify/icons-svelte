<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po701ib8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="po701ib8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diamond-half" {...props}></Icon>
