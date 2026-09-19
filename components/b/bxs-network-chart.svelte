<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzs4t1bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzs4t1bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-network-chart" {...props}></Icon>
