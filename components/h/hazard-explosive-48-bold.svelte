<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2mjsubix.css';
import '../../css/c/cedta078t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="cedta078t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-explosive-48-bold" {...props}></Icon>
