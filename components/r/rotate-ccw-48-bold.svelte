<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7pegcc2c.css';
import '../../css/q/qb0cveb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h7pegcc2c"/><path class="qb0cveb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-ccw-48-bold" {...props}></Icon>
