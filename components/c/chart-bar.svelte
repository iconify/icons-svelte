<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtjsgpbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rtjsgpbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-bar" {...props}></Icon>
