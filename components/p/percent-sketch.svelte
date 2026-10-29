<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/teiclfxwa.css';
import '../../css/k/ki722bqyl.css';
import '../../css/o/oaan660fk.css';
import '../../css/a/a-cpzbx-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="teiclfxwa"/><path class="ki722bqyl wm-k"/><path class="oaan660fk wm-k"/><path class="a-cpzbx-q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:percent-sketch" {...props}></Icon>
