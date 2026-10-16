<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_zzgnel.css';
import '../../css/c/c3wcvtp6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="c3wcvtp6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-gibbous-48" {...props}></Icon>
