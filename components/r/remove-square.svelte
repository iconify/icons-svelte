<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drmj1obvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drmj1obvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-square" {...props}></Icon>
