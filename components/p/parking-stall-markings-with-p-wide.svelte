<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0wz6zwkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m0wz6zwkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parking-stall-markings-with-p-wide" {...props}></Icon>
