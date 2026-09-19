<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-ys9t3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="wk-ys9t3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:google" {...props}></Icon>
