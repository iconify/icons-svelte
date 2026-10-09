<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi7uye37o.css';
import '../../css/c/cuecz6ezx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fi7uye37o"/><path class="cuecz6ezx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:files-48-bold" {...props}></Icon>
