<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz4_n_nrk.css';
import '../../css/i/ipw0oib4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jz4_n_nrk"/><path class="ipw0oib4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fava-light" {...props}></Icon>
