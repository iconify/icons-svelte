<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/ha1m0acqh.css';
import '../../css/w/wkxwu3bsi.css';
import '../../css/i/i1vxufb7n.css';
import '../../css/f/fxoqbf0fg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyzgoLcxy"><g class="v3_i3wktz"><path class="ha1m0acqh"/><path class="wkxwu3bsi"/><path class="i1vxufb7n"/><path class="fxoqbf0fg"/></g></mask></defs><path mask="url(#SVGyzgoLcxy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mail-review" {...props}></Icon>
