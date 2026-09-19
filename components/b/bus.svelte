<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r_6nlzbtv.css';
import '../../css/l/l-hm_u4_z.css';
import '../../css/a/appofdctq.css';
import '../../css/q/qig_zznph.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOR8ep13r"><g class="v3_i3wktz"><path class="r_6nlzbtv"/><path class="l-hm_u4_z"/><path class="appofdctq"/><path class="qig_zznph"/></g></mask></defs><path mask="url(#SVGOR8ep13r)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bus" {...props}></Icon>
