<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl0lw_beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl0lw_beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-right" {...props}></Icon>
