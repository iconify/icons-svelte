<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7p4ty4tq.css';
import '../../css/l/le-nvlb3m.css';
import '../../css/w/wb9zveb9j.css';
import '../../css/h/h0wnxs_dh.css';
import '../../css/a/a4j_ndb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":335.589,"height":80.057,"left":21.705,"top":19.44};
const content = `<g class="bi12bsetm"><path class="q7p4ty4tq"/><path class="le-nvlb3m"/><path class="wb9zveb9j"/><path class="h0wnxs_dh"/><path class="a4j_ndb_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:axure" {...props}></Icon>
