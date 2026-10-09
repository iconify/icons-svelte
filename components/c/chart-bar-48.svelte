<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9l2qqe6j.css';
import '../../css/b/bkiex1byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l2qqe6j"/><path class="bkiex1byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-48" {...props}></Icon>
