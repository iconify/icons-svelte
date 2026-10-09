<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5sdatbxs.css';
import '../../css/e/e0qbytbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k5sdatbxs"/><path class="e0qbytbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-cream-48" {...props}></Icon>
