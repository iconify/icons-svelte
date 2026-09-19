<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4d54nbgi.css';
import '../../css/n/nvnb2yl3l.css';
import '../../css/s/s164q9ezg.css';
import '../../css/q/qgisv1b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4d54nbgi"/><path class="nvnb2yl3l"/><path class="s164q9ezg"/><path class="qgisv1b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:framewithx" {...props}></Icon>
