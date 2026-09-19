<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sz9e8238f.css';
import '../../css/k/kxnbaldms.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoDnRsbqV"><g class="aql7dnt-u"><path class="sz9e8238f"/><path class="kxnbaldms"/></g></mask></defs><path mask="url(#SVGoDnRsbqV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:coat-hanger" {...props}></Icon>
