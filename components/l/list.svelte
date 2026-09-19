<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn2r_k_3k.css';
import '../../css/t/tng0ocbay.css';
import '../../css/w/wk855qbpc.css';
import '../../css/c/csbi0o7qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":11};
const content = `<circle class="tn2r_k_3k"/><circle class="tng0ocbay"/><circle class="wk855qbpc"/><path class="csbi0o7qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:list" {...props}></Icon>
