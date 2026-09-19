<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps6n6j5jn.css';
import '../../css/t/ttigw5b6h.css';
import '../../css/e/ej8id9bze.css';
import '../../css/e/eyppoibfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps6n6j5jn"/><path class="ttigw5b6h"/><path class="ej8id9bze"/><path class="eyppoibfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bunny" {...props}></Icon>
