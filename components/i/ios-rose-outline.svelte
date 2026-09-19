<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-u__gbwn.css';
import '../../css/i/ipbc4vbmv.css';
import '../../css/c/c19rfsb2z.css';
import '../../css/f/f3if6-vqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-u__gbwn"/><path class="ipbc4vbmv"/><path class="c19rfsb2z"/><path class="f3if6-vqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rose-outline" {...props}></Icon>
