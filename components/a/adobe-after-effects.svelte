<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl73selcd.css';
import '../../css/z/zusvsjbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl73selcd"/><path class="zusvsjbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-after-effects" {...props}></Icon>
