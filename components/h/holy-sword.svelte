<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/alx8q2bso.css';
import '../../css/a/as6-xr61g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWZkSzcLz"><g class="aql7dnt-u"><path class="alx8q2bso"/><path class="as6-xr61g"/></g></mask></defs><path mask="url(#SVGWZkSzcLz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:holy-sword" {...props}></Icon>
