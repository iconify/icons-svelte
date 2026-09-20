<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e7-fhk4_d.css';
import '../../css/l/lwpyjib8f.css';
import '../../css/u/up2lhibkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e7-fhk4_d"/><path class="lwpyjib8f"/><path class="up2lhibkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:job-seach-man" {...props}></Icon>
