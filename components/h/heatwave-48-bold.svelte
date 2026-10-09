<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz-knsbvd.css';
import '../../css/l/lj7gdpblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vz-knsbvd"/><path class="lj7gdpblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heatwave-48-bold" {...props}></Icon>
