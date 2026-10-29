<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oowq1xd7l.css';
import '../../css/r/ri9pveb6w.css';
import '../../css/i/i2-mb_b3z.css';
import '../../css/o/oa1gtpbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oowq1xd7l"/><path class="ri9pveb6w wm-a"/><path class="i2-mb_b3z wm-k"/><path class="oa1gtpbec wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-plus-sketch" {...props}></Icon>
