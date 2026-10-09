<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mheydraer.css';
import '../../css/b/b4g0wlvcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mheydraer"/><path class="b4g0wlvcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-triangle-48-bold" {...props}></Icon>
