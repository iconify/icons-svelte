<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ck_7agkxz.css';
import '../../css/l/lmtlhobkp.css';
import '../../css/y/yjlljib5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ck_7agkxz"/><path class="lmtlhobkp"/><path class="yjlljib5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-activity-duotone" {...props}></Icon>
