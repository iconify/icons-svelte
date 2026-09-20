<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd_g-pzxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yd_g-pzxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:eye" {...props}></Icon>
