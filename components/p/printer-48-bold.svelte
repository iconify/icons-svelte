<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhrxslnmz.css';
import '../../css/a/a65l708qm.css';
import '../../css/h/hd4-lcb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jhrxslnmz"/><path class="a65l708qm"/><path class="hd4-lcb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:printer-48-bold" {...props}></Icon>
