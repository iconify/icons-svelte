<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gte4k_rwf.css';
import '../../css/l/lmhgg8f3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gte4k_rwf"/><path class="lmhgg8f3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-stroke-20" {...props}></Icon>
