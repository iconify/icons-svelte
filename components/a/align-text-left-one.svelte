<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/n/n0_kkrbrg.css';
import '../../css/i/iu_7h2b0u.css';
import '../../css/n/n_o3cqb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="utf5_xbzs"/><path class="n0_kkrbrg"/><path class="iu_7h2b0u"/><path class="n_o3cqb8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:align-text-left-one" {...props}></Icon>
