<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/svu_ojrck.css';
import '../../css/l/l3j6m8bxm.css';
import '../../css/n/n2kxb8blp.css';
import '../../css/i/ip9ou-86q.css';
import '../../css/o/opvnhmoea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="svu_ojrck wm-k"/><path class="l3j6m8bxm wm-shadow"/><path class="n2kxb8blp wm-k"/><path class="ip9ou-86q wm-k"/><path class="opvnhmoea wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:history-engrave" {...props}></Icon>
