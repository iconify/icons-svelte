<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz3csgbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cz3csgbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-dashboard-20-bold" {...props}></Icon>
