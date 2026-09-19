<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioq_pnb1t.css';
import '../../css/x/xde3kv5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ioq_pnb1t"/><path class="xde3kv5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:golf-sharp" {...props}></Icon>
