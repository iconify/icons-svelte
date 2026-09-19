<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhnlhhbgn.css';
import '../../css/t/t4_f6k39w.css';
import '../../css/u/uizh__bvn.css';
import '../../css/k/khlacg85o.css';
import '../../css/x/x7iyjcc3y.css';
import '../../css/c/c4hrshagc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nhnlhhbgn"/><path class="t4_f6k39w"/><path class="uizh__bvn"/><path class="khlacg85o"/><path class="x7iyjcc3y"/><path class="c4hrshagc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:huoshanzhibo" {...props}></Icon>
