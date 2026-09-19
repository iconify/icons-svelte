<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/vi1h83lon.css';
import '../../css/w/wktsztbxm.css';
import '../../css/z/zaa5pgbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="vi1h83lon"/><path class="wktsztbxm"/><path class="zaa5pgbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:be" {...props}></Icon>
