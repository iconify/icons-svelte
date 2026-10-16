<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njwg_cbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="njwg_cbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-moon-rain-48-bold" {...props}></Icon>
