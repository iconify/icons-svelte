<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzy0f__1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tzy0f__1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:refused" {...props}></Icon>
