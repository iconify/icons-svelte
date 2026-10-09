<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpjugbvy.css';
import '../../css/z/z-tcgdc3x.css';
import '../../css/p/p_uvnbins.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="z-tcgdc3x"/><path class="p_uvnbins"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-plug-48-bold" {...props}></Icon>
