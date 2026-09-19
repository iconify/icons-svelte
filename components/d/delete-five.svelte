<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/b5kbnzv_b.css';
import '../../css/m/m_gx1l90r.css';
import '../../css/n/nzqb6cb6b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOsACrbJG"><g class="v3_i3wktz"><path class="b5kbnzv_b"/><path class="m_gx1l90r"/><path class="nzqb6cb6b"/></g></mask></defs><path mask="url(#SVGOsACrbJG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:delete-five" {...props}></Icon>
