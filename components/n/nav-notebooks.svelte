<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am_4qubdp.css';
import '../../css/l/l70u19-fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="am_4qubdp"/><path class="l70u19-fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-notebooks" {...props}></Icon>
