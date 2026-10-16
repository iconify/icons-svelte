<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf5g0ffhl.css';
import '../../css/h/huv6-s8fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cf5g0ffhl"/><path class="huv6-s8fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-detector-20" {...props}></Icon>
