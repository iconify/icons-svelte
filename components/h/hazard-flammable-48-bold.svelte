<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2mjsubix.css';
import '../../css/u/ub9hmvbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="ub9hmvbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-flammable-48-bold" {...props}></Icon>
