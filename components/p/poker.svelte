<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sxx9kbcui.css';
import '../../css/u/u-7u5koqq.css';
import '../../css/d/dt7mfmbea.css';
import '../../css/y/y0t2_6s_t.css';
import '../../css/q/qnx9txbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="sxx9kbcui"/><path clip-rule="evenodd" class="u-7u5koqq"/><path class="dt7mfmbea"/><path class="y0t2_6s_t"/><path class="qnx9txbsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:poker" {...props}></Icon>
