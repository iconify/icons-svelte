<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxs7g9ljm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":463,"height":463};
const content = `<path class="sxs7g9ljm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openfga" {...props}></Icon>
