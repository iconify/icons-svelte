<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvi4-tbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lvi4-tbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:map" {...props}></Icon>
