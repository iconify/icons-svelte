<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ldmla3b0f.css';
import '../../css/v/v59k4c3ri.css';
import '../../css/t/talm9jbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ldmla3b0f"/><rect transform="matrix(0 -1 -1 0 21.42 10.37)" class="v59k4c3ri"/><rect transform="matrix(0 -1 -1 0 21.42 10.37)" class="talm9jbul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:playlist-queue" {...props}></Icon>
