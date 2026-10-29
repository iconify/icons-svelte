<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/frpfn66gu.css';
import '../../css/m/me6kme-gu.css';
import '../../css/o/o2vm0kbuj.css';
import '../../css/g/gbftiw4sm.css';
import '../../css/e/eo-5y3hth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="frpfn66gu"/><path class="me6kme-gu"/><path class="o2vm0kbuj wm-a"/><path class="gbftiw4sm"/><path class="eo-5y3hth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:projector-duo" {...props}></Icon>
