<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/r9ztc99mw.css';
import '../../css/s/sqb547b2g.css';
import '../../css/m/m4vuqabns.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaNYVZseX"><g class="aql7dnt-u"><path class="r9ztc99mw"/><path clip-rule="evenodd" class="sqb547b2g"/><path class="m4vuqabns"/></g></mask></defs><path mask="url(#SVGaNYVZseX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ppt" {...props}></Icon>
