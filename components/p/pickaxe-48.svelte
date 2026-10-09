<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf2mm_--c.css';
import '../../css/k/kr_fs7b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tf2mm_--c"/><path class="kr_fs7b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickaxe-48" {...props}></Icon>
