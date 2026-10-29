<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hcigp2gnt.css';
import '../../css/k/kgga2ny9o.css';
import '../../css/t/tjlpedbiu.css';
import '../../css/l/lh_y89hot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hcigp2gnt"/><path class="kgga2ny9o wm-a"/><path class="tjlpedbiu wm-a"/><path class="lh_y89hot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:holly-duo" {...props}></Icon>
