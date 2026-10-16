<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq_9-8b5f.css';
import '../../css/d/dfsy1hrxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sq_9-8b5f"/><path class="dfsy1hrxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-network-48" {...props}></Icon>
