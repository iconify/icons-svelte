<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_ji1bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="zp_ji1bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:lego" {...props}></Icon>
