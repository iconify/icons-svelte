<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qgi8hqb5s.css';
import '../../css/f/frg6hh-gx.css';
import '../../css/d/dv0t7jb2h.css';
import '../../css/k/korl07bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qgi8hqb5s"/><path class="frg6hh-gx wm-a"/><path class="dv0t7jb2h wm-k"/><path class="korl07bdb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plus-circle-sketch" {...props}></Icon>
