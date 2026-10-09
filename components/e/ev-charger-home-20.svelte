<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m745xqbnl.css';
import '../../css/w/w39-xjyzv.css';
import '../../css/s/seqz3ibjg.css';
import '../../css/d/dse73pb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m745xqbnl"/><path class="w39-xjyzv"/><path class="seqz3ibjg"/><path class="dse73pb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-home-20" {...props}></Icon>
