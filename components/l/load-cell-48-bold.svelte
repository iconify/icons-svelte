<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_qrf6bex.css';
import '../../css/b/bwg811bpd.css';
import '../../css/o/orqjejdjp.css';
import '../../css/v/vlrk2yboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m_qrf6bex"/><path class="bwg811bpd"/><path class="orqjejdjp"/><path class="vlrk2yboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-cell-48-bold" {...props}></Icon>
