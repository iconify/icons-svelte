<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9czz4bal.css';
import '../../css/l/laagh_b7q.css';
import '../../css/q/q1ee2b8fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="laagh_b7q"/><path class="q1ee2b8fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-plug-48" {...props}></Icon>
