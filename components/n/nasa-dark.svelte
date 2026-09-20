<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzdafi6np.css';
import '../../css/x/xlao23b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzdafi6np"/><path class="xlao23b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-dark" {...props}></Icon>
