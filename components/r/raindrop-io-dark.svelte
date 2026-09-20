<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqr3-dvvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqr3-dvvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raindrop-io-dark" {...props}></Icon>
