<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw_1otbkh.css';
import '../../css/e/ed7w77b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rw_1otbkh"/><path class="ed7w77b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dashboard-48-bold" {...props}></Icon>
