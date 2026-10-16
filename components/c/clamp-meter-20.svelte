<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnhcupbsa.css';
import '../../css/f/f3bevmfxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wnhcupbsa"/><path class="f3bevmfxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clamp-meter-20" {...props}></Icon>
