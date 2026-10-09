<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbzdxvbap.css';
import '../../css/k/kc18vwbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mbzdxvbap"/><path class="kc18vwbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-air-balloon-48-bold" {...props}></Icon>
