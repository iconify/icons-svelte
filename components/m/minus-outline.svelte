<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn_gf0ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xn_gf0ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:minus-outline" {...props}></Icon>
