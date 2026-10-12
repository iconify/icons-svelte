<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq31kobat.css';
import '../../css/x/xcgq2ybhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rq31kobat"/><path class="xcgq2ybhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-chip-48" {...props}></Icon>
