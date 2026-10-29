<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iw7sgcb0o.css';
import '../../css/m/made-2n8s.css';
import '../../css/o/o2-y213ts.css';
import '../../css/g/gww7jop3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iw7sgcb0o"/><path class="made-2n8s wm-a"/><path class="o2-y213ts wm-k"/><path class="gww7jop3j wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-moon-sketch" {...props}></Icon>
