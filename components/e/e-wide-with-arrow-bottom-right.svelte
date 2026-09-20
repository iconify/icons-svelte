<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd_uy6b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wd_uy6b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:e-wide-with-arrow-bottom-right" {...props}></Icon>
