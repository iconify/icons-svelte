<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-o60sb2m.css';
import '../../css/l/lr2ntzbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e-o60sb2m"/><path class="lr2ntzbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-48" {...props}></Icon>
