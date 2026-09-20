<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7x5h9bzy.css';
import '../../css/x/xngc3ulnv.css';
import '../../css/f/fv87_ubng.css';
import '../../css/b/b4i6z6bsf.css';
import '../../css/g/g6cxb9b9r.css';
import '../../css/s/snp287xku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7x5h9bzy"/><path class="xngc3ulnv"/><path class="fv87_ubng"/><path class="b4i6z6bsf"/><path class="g6cxb9b9r"/><path class="snp287xku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:egypt" {...props}></Icon>
