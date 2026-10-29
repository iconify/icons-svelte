<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fgqe3-b2w.css';
import '../../css/r/r315h5b8w.css';
import '../../css/o/ozp63ob-s.css';
import '../../css/y/y3j3vjb4e.css';
import '../../css/z/zrrjdvbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fgqe3-b2w wm-k"/><path class="r315h5b8w wm-a"/><path class="ozp63ob-s wm-shadow"/><path class="wm-k y3j3vjb4e"/><path class="wm-a zrrjdvbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-engrave" {...props}></Icon>
