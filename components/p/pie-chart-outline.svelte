<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckanf-3yy.css';
import '../../css/h/h-c11pbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckanf-3yy"/><path class="h-c11pbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pie-chart-outline" {...props}></Icon>
