<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/c/c_r9ymrlo.css';
import '../../css/e/ee12-ya6f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtaGLabXy"><g class="aql7dnt-u"><path class="c_r9ymrlo"/><path class="ee12-ya6f"/></g></mask></defs><path mask="url(#SVGtaGLabXy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:repair" {...props}></Icon>
