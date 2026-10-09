<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnmx-0bxp.css';
import '../../css/h/h84xrioyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mnmx-0bxp"/><path class="h84xrioyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-island-48" {...props}></Icon>
