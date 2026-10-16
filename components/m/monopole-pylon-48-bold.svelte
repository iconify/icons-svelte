<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fif1fofps.css';
import '../../css/k/kj_8dbkmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fif1fofps"/><path class="kj_8dbkmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopole-pylon-48-bold" {...props}></Icon>
