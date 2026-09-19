<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbi1web-l.css';
import '../../css/c/c8qbtokgo.css';
import '../../css/l/l-0qr7dzn.css';
import '../../css/q/qvmzwopuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wbi1web-l"/><path class="c8qbtokgo"/><path class="l-0qr7dzn"/><path class="qvmzwopuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:envelopewithlightning" {...props}></Icon>
