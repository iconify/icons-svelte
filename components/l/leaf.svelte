<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcv4s00xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcv4s00xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:leaf" {...props}></Icon>
