<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/n/ng2u88qjz.css';
import '../../css/p/pfipa5buf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNIXFNeRn"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="ng2u88qjz"/><path class="pfipa5buf"/></g></mask></defs><path mask="url(#SVGNIXFNeRn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:new-picture" {...props}></Icon>
