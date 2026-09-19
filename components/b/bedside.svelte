<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/d5rlwhbfc.css';
import '../../css/u/uff8ilbxx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgWHeveXs"><g class="aql7dnt-u"><path class="d5rlwhbfc"/><path class="uff8ilbxx"/></g></mask></defs><path mask="url(#SVGgWHeveXs)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bedside" {...props}></Icon>
