<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzjqs1bbd.css';
import '../../css/k/kx75bricy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzjqs1bbd"/><path class="kx75bricy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:file-tray-outline" {...props}></Icon>
