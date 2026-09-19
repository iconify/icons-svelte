<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/idjlyibdv.css';
import '../../css/l/lqs9vvb0u.css';
import '../../css/q/q_6picbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="idjlyibdv"/><path class="lqs9vvb0u"/><path class="q_6picbex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:email-down" {...props}></Icon>
