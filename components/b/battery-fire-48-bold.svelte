<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpjq1ubkk.css';
import '../../css/m/mbu6h6bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xpjq1ubkk"/><path class="mbu6h6bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-fire-48-bold" {...props}></Icon>
