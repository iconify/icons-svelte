<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xey7e3bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xey7e3bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:loading-compact" {...props}></Icon>
