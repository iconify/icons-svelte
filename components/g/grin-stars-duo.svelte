<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/s/ss7mjkn-o.css';
import '../../css/a/a8924ab8w.css';
import '../../css/j/jboz1xbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="ss7mjkn-o"/><path class="a8924ab8w"/><path class="jboz1xbxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-stars-duo" {...props}></Icon>
