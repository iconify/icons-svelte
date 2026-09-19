<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/opl6_qb9p.css';
import '../../css/h/h6qog1b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":151};
const content = `<g class="ft5dv1b6b"><path class="opl6_qb9p"/><path class="h6qog1b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:ng" {...props}></Icon>
