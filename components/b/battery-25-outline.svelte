<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg96irb-q.css';
import '../../css/k/k2j2evb2o.css';
import '../../css/a/a2kumftht.css';
import '../../css/r/rbvbd_b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rg96irb-q"/><path clip-rule="evenodd" class="k2j2evb2o"/><path class="a2kumftht"/><path clip-rule="evenodd" class="rbvbd_b7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-25-outline" {...props}></Icon>
