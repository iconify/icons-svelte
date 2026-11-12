<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6szscc-u.css';
import '../../css/w/w5t1ykp4g.css';
import '../../css/s/slveivbkv.css';
import '../../css/l/l4067mbwa.css';
import '../../css/q/qopzznmys.css';
import '../../css/g/gep5gvj9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w6szscc-u"/><path class="w5t1ykp4g"/><path class="slveivbkv"/><circle class="l4067mbwa"/><path class="qopzznmys"/><path class="gep5gvj9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudreve" {...props}></Icon>
