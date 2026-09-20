<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw1_f1dns.css';
import '../../css/w/w5t1ykp4g.css';
import '../../css/s/slveivbkv.css';
import '../../css/t/tlcbsubgk.css';
import '../../css/q/qopzznmys.css';
import '../../css/g/gep5gvj9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bw1_f1dns"/><path class="w5t1ykp4g"/><path class="slveivbkv"/><circle class="tlcbsubgk"/><path class="qopzznmys"/><path class="gep5gvj9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudreve" {...props}></Icon>
