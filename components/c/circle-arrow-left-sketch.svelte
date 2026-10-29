<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zy4827b2t.css';
import '../../css/x/x_vesxj5e.css';
import '../../css/x/xp6eksv1n.css';
import '../../css/t/thpiy8vsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zy4827b2t"/><path class="wm-k x_vesxj5e"/><path class="wm-a xp6eksv1n"/><path class="thpiy8vsx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-left-sketch" {...props}></Icon>
