<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvmv32bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mvmv32bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freefinance-dark" {...props}></Icon>
