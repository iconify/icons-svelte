<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry8bitgof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ry8bitgof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prestashop-dark" {...props}></Icon>
