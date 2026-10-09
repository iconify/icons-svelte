<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxbs21b9m.css';
import '../../css/d/dekgiyoss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zxbs21b9m"/><path class="dekgiyoss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-48" {...props}></Icon>
