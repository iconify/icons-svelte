<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmxox-big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lmxox-big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:percent-48" {...props}></Icon>
