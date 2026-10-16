<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l10uce2pa.css';
import '../../css/o/ou2ox_rmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l10uce2pa"/><path class="ou2ox_rmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dew-48" {...props}></Icon>
