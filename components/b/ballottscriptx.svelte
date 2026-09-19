<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2p2k_glq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2p2k_glq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ballottscriptx" {...props}></Icon>
