<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbb3y-lxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kbb3y-lxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:leftspeechbubble" {...props}></Icon>
