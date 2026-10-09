<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_cnnjai.css';
import '../../css/q/qi1j3qboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h-_cnnjai"/><path class="qi1j3qboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-sankey-48-bold" {...props}></Icon>
