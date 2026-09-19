<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g86p7cczn.css';
import '../../css/e/eb847rttw.css';
import '../../css/d/d28pnkcvk.css';
import '../../css/h/hhonhdeix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g86p7cczn"/><path class="eb847rttw"/><path class="d28pnkcvk"/><path class="hhonhdeix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:roastedsweetpotato" {...props}></Icon>
