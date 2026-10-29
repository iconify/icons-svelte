<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gie3geb9a.css';
import '../../css/f/f33oscbyn.css';
import '../../css/o/o_ba6fyis.css';
import '../../css/d/ds28d454v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gie3geb9a"/><path class="f33oscbyn wm-k"/><path class="o_ba6fyis wm-k"/><path class="ds28d454v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:library-sketch" {...props}></Icon>
