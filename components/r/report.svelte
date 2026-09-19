<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dn5joqb2b.css';
import '../../css/l/lqwcol_8m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNbbQMcwu"><g class="v3_i3wktz"><path class="dn5joqb2b"/><path class="lqwcol_8m"/></g></mask></defs><path mask="url(#SVGNbbQMcwu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:report" {...props}></Icon>
