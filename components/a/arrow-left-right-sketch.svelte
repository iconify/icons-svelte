<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lssi5abca.css';
import '../../css/m/m28utr75s.css';
import '../../css/e/evyvslb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lssi5abca wm-a"/><path class="m28utr75s wm-k"/><path class="evyvslb3y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-right-sketch" {...props}></Icon>
