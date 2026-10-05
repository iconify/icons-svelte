<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fcy8up5fy.css';
import '../../css/x/x5ducvb9i.css';
import '../../css/a/a36t_bc_w.css';
import '../../css/s/sjk64dfcn.css';
import '../../css/x/xjgy_cbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fcy8up5fy"/><path class="x5ducvb9i"/><path class="a36t_bc_w"/><path class="sjk64dfcn"/><path class="xjgy_cbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:paperclip" {...props}></Icon>
