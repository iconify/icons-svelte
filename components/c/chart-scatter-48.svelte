<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdp5l0b5n.css';
import '../../css/z/zyix_fbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qdp5l0b5n"/><path class="zyix_fbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-scatter-48" {...props}></Icon>
