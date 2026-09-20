<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzvaq3_vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzvaq3_vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:online-gateway-outline" {...props}></Icon>
