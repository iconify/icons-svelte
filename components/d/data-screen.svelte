<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/ocu06zbra.css';
import '../../css/b/b5yxc2b_y.css';
import '../../css/m/mdnlgwb3d.css';
import '../../css/o/oynk-s10v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoWG3zdla"><g class="aql7dnt-u"><rect class="ocu06zbra"/><path class="b5yxc2b_y"/><circle class="mdnlgwb3d"/><circle class="oynk-s10v"/></g></mask></defs><path mask="url(#SVGoWG3zdla)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:data-screen" {...props}></Icon>
