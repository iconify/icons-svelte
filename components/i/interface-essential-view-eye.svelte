<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5t413bgn.css';
import '../../css/o/oktelfbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w5t413bgn"/><path class="oktelfbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-view-eye" {...props}></Icon>
