<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/cw-iw1_ie.css';
import '../../css/i/im6flx-ax.css';
import '../../css/z/z-phgabtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="cw-iw1_ie"/><path class="im6flx-ax"/><path class="z-phgabtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:ghost" {...props}></Icon>
