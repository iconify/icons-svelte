<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_zzgnel.css';
import '../../css/m/ml2cy1-1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="ml2cy1-1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-crescent-48" {...props}></Icon>
