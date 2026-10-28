<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7b6qsb4o.css';
import '../../css/j/ju78x-kpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m7b6qsb4o"/><path class="ju78x-kpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nostos" {...props}></Icon>
