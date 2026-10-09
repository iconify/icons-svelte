<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e43ajkbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e43ajkbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rare-earth-48" {...props}></Icon>
