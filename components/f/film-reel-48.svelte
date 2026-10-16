<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmgtk8bav.css';
import '../../css/k/k4873id8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vmgtk8bav"/><path class="k4873id8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-reel-48" {...props}></Icon>
