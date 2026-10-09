<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e84_f2b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e84_f2b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-48-bold" {...props}></Icon>
