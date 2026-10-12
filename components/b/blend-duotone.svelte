<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kwvz9gbdr.css';
import '../../css/x/xf1rtpbyd.css';
import '../../css/m/mqc3cacsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwvz9gbdr"/><path class="xf1rtpbyd"/><path class="mqc3cacsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:blend-duotone" {...props}></Icon>
