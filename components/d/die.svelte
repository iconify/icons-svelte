<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1iqpboh.css';
import '../../css/k/k79q3xboj.css';
import '../../css/r/r5d2n_xgw.css';
import '../../css/w/w23d_qkzq.css';
import '../../css/z/zxhjaubkm.css';
import '../../css/g/gx7dd0bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="od1iqpboh"/><circle class="k79q3xboj"/><circle class="r5d2n_xgw"/><circle class="w23d_qkzq"/><circle class="zxhjaubkm"/><circle class="gx7dd0bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:die" {...props}></Icon>
