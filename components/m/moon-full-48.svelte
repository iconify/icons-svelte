<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_zzgnel.css';
import '../../css/h/hqyn3psnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="hqyn3psnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-full-48" {...props}></Icon>
