<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbt4ulf2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":488};
const content = `<path class="hbt4ulf2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:facebook-places" {...props}></Icon>
