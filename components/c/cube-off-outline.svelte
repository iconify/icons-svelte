<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmr3c33eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmr3c33eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cube-off-outline" {...props}></Icon>
