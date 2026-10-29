<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hlkyzpb5b.css';
import '../../css/g/gjmv2fbbd.css';
import '../../css/x/xpcuehkpf.css';
import '../../css/j/j579kzbfd.css';
import '../../css/z/z_db1muvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hlkyzpb5b wm-k"/><path class="gjmv2fbbd wm-a"/><path class="wm-shadow xpcuehkpf"/><path class="j579kzbfd wm-a"/><path class="wm-k z_db1muvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-to-line-engrave" {...props}></Icon>
