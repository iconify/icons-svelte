<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsnsvvblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gsnsvvblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-cubes-to-cup-from-dispensing-machine-with-snowflake" {...props}></Icon>
