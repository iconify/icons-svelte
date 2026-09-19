<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdx7ncbbp.css';
import '../../css/l/lyxkoik3t.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 sdx7ncbbp"/><path class="clr-i-solid clr-i-solid-path-2 lyxkoik3t"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:camera-solid" {...props}></Icon>
