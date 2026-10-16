<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5rak2bbx.css';
import '../../css/q/qnvn8ia7m.css';
import '../../css/v/vai4pdqog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5rak2bbx"/><path class="qnvn8ia7m"/><path class="vai4pdqog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ceiling-light-48-bold" {...props}></Icon>
