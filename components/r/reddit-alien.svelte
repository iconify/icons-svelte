<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrjct8wjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrjct8wjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:reddit-alien" {...props}></Icon>
