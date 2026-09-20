<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4v2btb9e.css';
import '../../css/y/ykliw_bta.css';
import '../../css/o/ozeko6bkf.css';
import '../../css/s/szx5y9bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t4v2btb9e"/><circle class="ykliw_bta"/><circle class="ozeko6bkf"/><circle class="szx5y9bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:palette-ltr" {...props}></Icon>
