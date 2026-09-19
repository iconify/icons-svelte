<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/k/ki6skwu5m.css';
import '../../css/l/lud_wla_u.css';
import '../../css/t/t33jx3cgu.css';
import '../../css/v/vvnugib5y.css';
import '../../css/p/p_sx7ibve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="ki6skwu5m"/><path clip-rule="evenodd" class="lud_wla_u"/><path class="t33jx3cgu"/><path class="vvnugib5y"/><path class="p_sx7ibve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:radar" {...props}></Icon>
