<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ara7uci.css';
import '../../css/y/yt1kjcbtq.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j-ara7uci"/><path class="yt1kjcbtq"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-paid-20" {...props}></Icon>
