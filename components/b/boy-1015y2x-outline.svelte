<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drv7s9bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="drv7s9bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:boy-1015y2x-outline" {...props}></Icon>
