<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cjlnqmbsm.css';
import '../../css/e/ertd60wwo.css';
import '../../css/b/b7i_kkbbz.css';
import '../../css/l/l22tp1dfe.css';
import '../../css/u/ubywv1b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cjlnqmbsm"/><path class="ertd60wwo wm-k"/><path class="b7i_kkbbz wm-k"/><path class="l22tp1dfe wm-a"/><path class="ubywv1b8a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-low-sketch" {...props}></Icon>
