<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5ps2pbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ps2pbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-percentage" {...props}></Icon>
