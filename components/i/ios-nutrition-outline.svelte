<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcj3c8bij.css';
import '../../css/w/w5w3u0b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcj3c8bij"/><path class="w5w3u0b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-nutrition-outline" {...props}></Icon>
