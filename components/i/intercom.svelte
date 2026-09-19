<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/r_dv08lvg.css';
import '../../css/j/j54835brq.css';
import '../../css/m/m8p9je9sb.css';
import '../../css/i/ieu4x_bor.css';
import '../../css/r/rp1vnt36c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="r_dv08lvg"/><path class="j54835brq"/><path class="m8p9je9sb"/><path class="ieu4x_bor"/><path class="rp1vnt36c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:intercom" {...props}></Icon>
