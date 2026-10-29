<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l67s7zbss.css';
import '../../css/o/opvnhmoea.css';
import '../../css/n/n2kxb8blp.css';
import '../../css/i/ip9ou-86q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l67s7zbss"/><path class="opvnhmoea wm-a"/><path class="n2kxb8blp"/><path class="ip9ou-86q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:history-duo" {...props}></Icon>
