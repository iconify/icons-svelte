<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it4d2uboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="it4d2uboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-play" {...props}></Icon>
