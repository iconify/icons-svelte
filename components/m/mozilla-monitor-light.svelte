<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3y6xqgne.css';
import '../../css/p/p84959bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3y6xqgne"/><path class="p84959bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-monitor-light" {...props}></Icon>
