<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhbtucwnq.css';
import '../../css/c/ckrfkccuv.css';
import '../../css/u/ugul67fgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhbtucwnq"/><ellipse class="ckrfkccuv"/><path class="ugul67fgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etesync" {...props}></Icon>
