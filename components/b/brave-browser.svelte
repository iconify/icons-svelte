<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilbm1ebie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbm1ebie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:brave-browser" {...props}></Icon>
