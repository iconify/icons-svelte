<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rgp0nubmz.css';
import '../../css/x/xyfvrf3td.css';
import '../../css/w/w6xr20wbw.css';
import '../../css/p/p9b3hul9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rgp0nubmz"/><path class="xyfvrf3td"/><path class="w6xr20wbw"/><path class="p9b3hul9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:image-1-outline" {...props}></Icon>
