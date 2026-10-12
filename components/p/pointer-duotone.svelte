<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/la6rrxbig.css';
import '../../css/j/jziytlbpg.css';
import '../../css/p/p-xr52ctm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="la6rrxbig"/><path class="jziytlbpg"/><path class="p-xr52ctm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pointer-duotone" {...props}></Icon>
