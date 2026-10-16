<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ri8jbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7ri8jbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-dashboard-48-bold" {...props}></Icon>
