<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1xknbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oo1xknbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-dashboard-48" {...props}></Icon>
