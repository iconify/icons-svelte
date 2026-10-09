<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmdr1llum.css';
import '../../css/r/r0z87ttka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mmdr1llum"/><path class="r0z87ttka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-nacs-48-bold" {...props}></Icon>
