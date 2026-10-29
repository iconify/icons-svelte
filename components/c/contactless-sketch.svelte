<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekqmbnb8e.css';
import '../../css/c/ck8dhpbcc.css';
import '../../css/h/hje6bbbsd.css';
import '../../css/a/acoval0gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekqmbnb8e wm-k"/><path class="ck8dhpbcc wm-a"/><path class="hje6bbbsd wm-k"/><path class="acoval0gz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contactless-sketch" {...props}></Icon>
