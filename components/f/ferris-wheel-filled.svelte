<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4xr16b6e.css';
import '../../css/r/rsmwqzs4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4xr16b6e"/><path class="rsmwqzs4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ferris-wheel-filled" {...props}></Icon>
