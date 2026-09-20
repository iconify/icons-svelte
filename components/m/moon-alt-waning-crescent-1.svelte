<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxd78lb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="sxd78lb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-crescent-1" {...props}></Icon>
