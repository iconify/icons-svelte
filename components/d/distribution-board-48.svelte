<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvyikx3qg.css';
import '../../css/f/fwh01mbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qvyikx3qg"/><path class="fwh01mbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribution-board-48" {...props}></Icon>
