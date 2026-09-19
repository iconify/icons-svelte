<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zan3bnbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zan3bnbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:elementor" {...props}></Icon>
