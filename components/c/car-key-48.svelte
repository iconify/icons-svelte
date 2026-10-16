<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bazb3ccgr.css';
import '../../css/y/yy05a9bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bazb3ccgr"/><path class="yy05a9bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-key-48" {...props}></Icon>
