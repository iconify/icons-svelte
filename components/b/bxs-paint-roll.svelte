<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i37phhb_v.css';
import '../../css/u/uw6sq-v3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i37phhb_v"/><path class="uw6sq-v3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-paint-roll" {...props}></Icon>
