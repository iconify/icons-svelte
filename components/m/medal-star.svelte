<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tawrpdb4t.css';
import '../../css/m/mt3oabbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tawrpdb4t"/><path class="mt3oabbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-star" {...props}></Icon>
