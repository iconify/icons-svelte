<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ykm4gac9n.css';
import '../../css/u/ug04ojbab.css';
import '../../css/e/ec_xkzblh.css';
import '../../css/k/k0cxohbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ykm4gac9n"/><path class="ug04ojbab wm-a"/><path class="ec_xkzblh wm-k"/><path class="k0cxohbmd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-medical-sketch" {...props}></Icon>
