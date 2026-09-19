<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pfvzz0gys.css';
import '../../css/z/ze54d44ll.css';
import '../../css/k/kxs16xb2x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGXg2icVX"><g class="v3_i3wktz"><path class="pfvzz0gys"/><path class="ze54d44ll"/><path class="kxs16xb2x"/></g></mask></defs><path mask="url(#SVGGXg2icVX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:id-card" {...props}></Icon>
