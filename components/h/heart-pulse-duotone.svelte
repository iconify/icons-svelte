<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pp7gobvlg.css';
import '../../css/v/v1010nu4c.css';
import '../../css/q/qdusw7byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pp7gobvlg"/><path class="v1010nu4c"/><path class="qdusw7byz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-pulse-duotone" {...props}></Icon>
