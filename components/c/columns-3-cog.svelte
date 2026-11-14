<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voe_oxz9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voe_oxz9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:columns-3-cog" {...props}></Icon>
