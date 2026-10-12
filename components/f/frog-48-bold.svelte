<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi97z4bps.css';
import '../../css/r/rh7ug_byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mi97z4bps"/><path class="rh7ug_byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frog-48-bold" {...props}></Icon>
