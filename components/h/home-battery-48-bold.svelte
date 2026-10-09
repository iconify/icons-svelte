<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izjyqdbgb.css';
import '../../css/g/gqhyy7b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="izjyqdbgb"/><path class="gqhyy7b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-battery-48-bold" {...props}></Icon>
