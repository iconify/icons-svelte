<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwtif3bjl.css';
import '../../css/h/h02ib-6ed.css';
import '../../css/y/yjpow2b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwtif3bjl"/><path class="h02ib-6ed"/><path class="yjpow2b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:markschaptersymbol" {...props}></Icon>
