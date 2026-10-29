<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k0nqxxblh.css';
import '../../css/z/zm3ct5beq.css';
import '../../css/q/qerylv5lr.css';
import '../../css/r/r1w9erb-v.css';
import '../../css/g/grfsii31x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k0nqxxblh"/><path class="wm-k zm3ct5beq"/><path class="qerylv5lr wm-a"/><path class="r1w9erb-v wm-k"/><path class="grfsii31x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:firecracker-sketch" {...props}></Icon>
