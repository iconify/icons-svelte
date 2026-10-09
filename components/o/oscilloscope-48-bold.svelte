<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1y5cbbe.css';
import '../../css/x/x1xqvkh1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="x1xqvkh1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oscilloscope-48-bold" {...props}></Icon>
