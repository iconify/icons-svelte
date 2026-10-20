<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo64yvbkk.css';
import '../../css/q/q5h959_9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xo64yvbkk"/><path class="q5h959_9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-sparkle-48" {...props}></Icon>
