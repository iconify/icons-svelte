<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq1cssb6m.css';
import '../../css/e/ef6i17ddi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iq1cssb6m"/><path class="ef6i17ddi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladle-48" {...props}></Icon>
