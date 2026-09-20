<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/j/jzzx7m_6o.css';
import '../../css/a/avwbqkbxp.css';
import '../../css/e/e8utxjb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="jzzx7m_6o"/><path class="avwbqkbxp"/><path class="e8utxjb0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:jump-forward" {...props}></Icon>
