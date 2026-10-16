<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_12fhuiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g_12fhuiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apps-48" {...props}></Icon>
