<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ylf6w5b.css';
import '../../css/r/rt3j0ibnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m0ylf6w5b"/><path class="rt3j0ibnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:alarm" {...props}></Icon>
