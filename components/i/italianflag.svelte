<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kobakmnrv.css';
import '../../css/r/rcci-d4wx.css';
import '../../css/b/b197rfn0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kobakmnrv"/><path class="rcci-d4wx"/><path class="b197rfn0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:italianflag" {...props}></Icon>
