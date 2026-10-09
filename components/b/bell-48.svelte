<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hosli1blv.css';
import '../../css/f/frcqirb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hosli1blv"/><path class="frcqirb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-48" {...props}></Icon>
