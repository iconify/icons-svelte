<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwur6tzl.css';
import '../../css/l/l9ao81bdv.css';
import '../../css/x/xfmnipbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="awwur6tzl"/><path class="l9ao81bdv"/><path class="xfmnipbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-home-20-bold" {...props}></Icon>
