<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gbftiw4sm.css';
import '../../css/r/rmqzxtb-y.css';
import '../../css/o/o2vm0kbuj.css';
import '../../css/m/m3zf-tb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gbftiw4sm"/><path class="rmqzxtb-y"/><path class="o2vm0kbuj wm-a"/><path class="m3zf-tb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:projector" {...props}></Icon>
