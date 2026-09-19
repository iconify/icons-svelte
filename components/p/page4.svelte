<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laa4fbevb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="laa4fbevb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:page4" {...props}></Icon>
