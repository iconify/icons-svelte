<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8d66nlfs.css';
import '../../css/p/phox42bnd.css';
import '../../css/r/rmb7iccqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j8d66nlfs"/><path class="phox42bnd"/><path class="rmb7iccqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-off-48-bold" {...props}></Icon>
