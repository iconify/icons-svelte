<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1xiqqxwq.css';
import '../../css/u/uiavscbxc.css';
import '../../css/p/p_qrzz42h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="m1xiqqxwq"/><path class="uiavscbxc"/><path class="p_qrzz42h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:pakistan" {...props}></Icon>
