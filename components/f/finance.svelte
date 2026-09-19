<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/y/yl8nvnbzd.css';
import '../../css/b/bf33dpbcm.css';
import '../../css/i/i79-xgbhl.css';
import '../../css/i/i41iyybok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="yl8nvnbzd"/><path class="bf33dpbcm"/><path class="i79-xgbhl"/><path class="i41iyybok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:finance" {...props}></Icon>
