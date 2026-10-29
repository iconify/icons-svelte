<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j684kzbgo.css';
import '../../css/n/ndzwtnbsc.css';
import '../../css/q/q26pnyb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j684kzbgo"/><path class="ndzwtnbsc wm-k"/><path class="q26pnyb0v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ethernet-port-sketch" {...props}></Icon>
