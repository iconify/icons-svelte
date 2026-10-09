<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kccn7xs5a.css';
import '../../css/f/fbsv3bchb.css';
import '../../css/k/k0x9cnbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kccn7xs5a"/><path class="fbsv3bchb"/><path class="k0x9cnbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ferris-wheel-48-bold" {...props}></Icon>
