<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a12sn_bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="a12sn_bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:car-wash" {...props}></Icon>
