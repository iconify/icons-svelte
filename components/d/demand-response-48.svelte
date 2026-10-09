<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs75gccsu.css';
import '../../css/l/leqhccbhf.css';
import '../../css/e/e9wm7acuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zs75gccsu"/><path class="leqhccbhf"/><path class="e9wm7acuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:demand-response-48" {...props}></Icon>
