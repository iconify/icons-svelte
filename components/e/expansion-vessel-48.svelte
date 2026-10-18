<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps-cpeb9h.css';
import '../../css/e/ekaxy2bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ps-cpeb9h"/><path class="ekaxy2bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expansion-vessel-48" {...props}></Icon>
