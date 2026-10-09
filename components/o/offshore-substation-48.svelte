<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy4vy0gsk.css';
import '../../css/v/vxoaqbnzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sy4vy0gsk"/><path class="vxoaqbnzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-substation-48" {...props}></Icon>
