<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7o8wb3mz.css';
import '../../css/f/fcdm3_xoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x7o8wb3mz"/><path class="fcdm3_xoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-left-48" {...props}></Icon>
