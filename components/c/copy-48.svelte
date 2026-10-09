<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og2b0zuoz.css';
import '../../css/f/fi2nkdbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="og2b0zuoz"/><path class="fi2nkdbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copy-48" {...props}></Icon>
