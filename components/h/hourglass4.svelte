<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j06qx_bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j06qx_bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass4" {...props}></Icon>
