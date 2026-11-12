<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtmawi7ic.css';
import '../../css/e/e558ozb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtmawi7ic"/><path class="e558ozb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-light" {...props}></Icon>
