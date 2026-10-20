<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9l2qqe6j.css';
import '../../css/g/g_9d-k8ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l2qqe6j"/><path class="g_9d-k8ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-bottom-48" {...props}></Icon>
