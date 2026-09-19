<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p35kmxb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p35kmxb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:lastfm-square" {...props}></Icon>
