<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t048yihdc.css';
import '../../css/l/lap-h8eft.css';
import '../../css/f/fzlatcc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t048yihdc"/><path class="lap-h8eft"/><path class="fzlatcc_e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:door-open" {...props}></Icon>
