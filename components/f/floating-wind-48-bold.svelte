<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7qdlcbcy.css';
import '../../css/k/kynfjw24x.css';
import '../../css/t/tew95inet.css';
import '../../css/d/d26csiiuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p7qdlcbcy"/><path class="kynfjw24x"/><path class="tew95inet"/><path class="d26csiiuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floating-wind-48-bold" {...props}></Icon>
