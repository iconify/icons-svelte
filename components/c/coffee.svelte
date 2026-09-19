<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoam0_w_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="xoam0_w_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:coffee" {...props}></Icon>
