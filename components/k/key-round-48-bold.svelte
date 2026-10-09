<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2oawlg-q.css';
import '../../css/z/z7_88imtg.css';
import '../../css/z/zbidebcoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j2oawlg-q"/><path class="z7_88imtg"/><path class="zbidebcoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-round-48-bold" {...props}></Icon>
