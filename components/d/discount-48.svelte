<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntq5xn_m.css';
import '../../css/m/m9h-zrraw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wntq5xn_m"/><path class="m9h-zrraw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:discount-48" {...props}></Icon>
