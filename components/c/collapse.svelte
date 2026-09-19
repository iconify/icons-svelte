<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb8rx2b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb8rx2b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:collapse" {...props}></Icon>
