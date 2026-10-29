<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dpn050blv.css';
import '../../css/q/qvgoqkb4i.css';
import '../../css/c/cp8mn0bar.css';
import '../../css/g/gkwfuwbas.css';
import '../../css/c/ccfc4fbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><circle class="dpn050blv wm-k"/><path class="qvgoqkb4i wm-k"/><circle class="cp8mn0bar wm-a"/><circle class="gkwfuwbas wm-a"/><circle class="ccfc4fbte wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-wheelchair-blueprint" {...props}></Icon>
