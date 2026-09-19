<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/j/j_frwf33v.css';
import '../../css/g/gnr850uhy.css';
import '../../css/h/hl1e5tbjq.css';
import '../../css/a/a-2hqx3ud.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGv1fFy7IO"><g class="aql7dnt-u"><rect class="j_frwf33v"/><path class="gnr850uhy"/><path clip-rule="evenodd" class="hl1e5tbjq"/><path class="a-2hqx3ud"/></g></mask></defs><path mask="url(#SVGv1fFy7IO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:calendar-thirty" {...props}></Icon>
