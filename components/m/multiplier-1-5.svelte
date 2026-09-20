<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uywc1tb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="uywc1tb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:multiplier-1-5" {...props}></Icon>
