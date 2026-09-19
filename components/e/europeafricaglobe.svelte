<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzofhbcwo.css';
import '../../css/o/ow7bebbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzofhbcwo"/><path class="ow7bebbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:europeafricaglobe" {...props}></Icon>
