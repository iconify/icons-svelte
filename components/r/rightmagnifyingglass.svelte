<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbi0r-y8h.css';
import '../../css/n/ne4t_uv8b.css';
import '../../css/g/geasmbcqt.css';
import '../../css/t/tgw_nb89p.css';
import '../../css/g/ggx3qtb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbi0r-y8h"/><circle class="ne4t_uv8b"/><path class="geasmbcqt"/><path class="tgw_nb89p"/><path class="ggx3qtb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rightmagnifyingglass" {...props}></Icon>
