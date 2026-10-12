<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohs7hsjpb.css';
import '../../css/s/sdzy7xbyh.css';
import '../../css/j/j3w9z2dlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohs7hsjpb"/><path class="sdzy7xbyh"/><path class="j3w9z2dlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-engine-48" {...props}></Icon>
