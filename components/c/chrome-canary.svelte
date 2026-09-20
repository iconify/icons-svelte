<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb5m_klsf.css';
import '../../css/a/atfcwpbzs.css';
import '../../css/d/dhkrc6b7i.css';
import '../../css/f/f5iszbo2p.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/j/jj7lh75iy.css';
import '../../css/s/s8avn9bxr.css';
import '../../css/u/usozxnbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="sb5m_klsf"/><path clip-rule="evenodd" class="atfcwpbzs"/><path clip-rule="evenodd" class="dhkrc6b7i"/><circle class="f5iszbo2p"/><g class="brzn_0bpr"><circle class="jj7lh75iy"/><path class="s8avn9bxr"/><circle class="usozxnbrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:chrome-canary" {...props}></Icon>
