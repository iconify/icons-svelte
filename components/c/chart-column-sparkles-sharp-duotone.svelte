<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/i/i1_mvd76s.css';
import '../../css/a/aczsw8qlb.css';
import '../../css/n/nsmv8c5kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="i1_mvd76s"/><path class="aczsw8qlb"/><path class="nsmv8c5kg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-sparkles-sharp-duotone" {...props}></Icon>
