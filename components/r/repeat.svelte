<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5e6emb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5e6emb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:repeat" {...props}></Icon>
