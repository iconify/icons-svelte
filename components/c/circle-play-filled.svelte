<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0268fbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h0268fbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-play-filled" {...props}></Icon>
