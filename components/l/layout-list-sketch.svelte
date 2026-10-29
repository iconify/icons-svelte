<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l9khuwb9i.css';
import '../../css/n/njptybbfv.css';
import '../../css/n/nqru_n_7g.css';
import '../../css/q/qy7-phkvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l9khuwb9i"/><path class="njptybbfv wm-k"/><path class="nqru_n_7g wm-k"/><path class="qy7-phkvw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-list-sketch" {...props}></Icon>
