<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io5uy9biy.css';
import '../../css/m/mt5_qbbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="io5uy9biy"/><path class="mt5_qbbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-unread-48-bold" {...props}></Icon>
