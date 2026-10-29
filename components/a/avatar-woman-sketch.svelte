<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fxisi3e-m.css';
import '../../css/n/nijlxnzfg.css';
import '../../css/n/n10g9-b5w.css';
import '../../css/r/rpjj2abjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fxisi3e-m wm-k"/><path class="nijlxnzfg wm-a"/><path class="n10g9-b5w wm-k"/><path class="rpjj2abjl wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-sketch" {...props}></Icon>
