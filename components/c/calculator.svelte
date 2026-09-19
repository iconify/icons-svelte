<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tdp-hibex.css';
import '../../css/h/h33t9nb0m.css';
import '../../css/u/uihgw98am.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEm5JnRSN"><g class="v3_i3wktz"><path class="tdp-hibex"/><path class="h33t9nb0m"/><path class="uihgw98am"/></g></mask></defs><path mask="url(#SVGEm5JnRSN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:calculator" {...props}></Icon>
