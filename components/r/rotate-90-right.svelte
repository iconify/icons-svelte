<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ask_q2bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ask_q2bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rotate-90-right" {...props}></Icon>
