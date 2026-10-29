<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i6x_spqod.css';
import '../../css/a/ar8a0cboq.css';
import '../../css/k/kmspi9b9w.css';
import '../../css/i/i__yerbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i6x_spqod"/><path class="ar8a0cboq wm-k"/><path class="kmspi9b9w wm-k"/><path class="i__yerbdi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-bottom-sketch" {...props}></Icon>
