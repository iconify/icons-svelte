<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mf9tocc_c.css';
import '../../css/a/ar5vrmb3o.css';
import '../../css/l/lqn5i1b2i.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4r7KTbgb"><g class="aql7dnt-u"><path class="mf9tocc_c"/><path class="ar5vrmb3o"/><path class="lqn5i1b2i"/></g></mask></defs><path mask="url(#SVG4r7KTbgb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hot-pot" {...props}></Icon>
