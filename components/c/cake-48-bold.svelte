<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inuv3l36d.css';
import '../../css/z/zabxrlbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="inuv3l36d"/><path class="zabxrlbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cake-48-bold" {...props}></Icon>
