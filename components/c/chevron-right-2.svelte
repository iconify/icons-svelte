<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfmwsx5_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yfmwsx5_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-right-2" {...props}></Icon>
