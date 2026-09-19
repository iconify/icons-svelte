<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/fu68vabvx.css';
import '../../css/n/noo2m29ib.css';
import '../../css/b/b2n3vku2e.css';
import '../../css/v/vnfj97bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="fu68vabvx"/><path class="noo2m29ib"/><path class="b2n3vku2e"/><path class="vnfj97bbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:kanuri" {...props}></Icon>
