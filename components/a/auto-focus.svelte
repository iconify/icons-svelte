<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s6apofftk.css';
import '../../css/n/nsusglb8a.css';
import '../../css/l/lca41vbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="s6apofftk"/><circle transform="matrix(-1 0 0 1 24 24)" class="nsusglb8a"/><path class="lca41vbdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:auto-focus" {...props}></Icon>
