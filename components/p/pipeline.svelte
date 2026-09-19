<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj0y7_bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0y7_bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pipeline" {...props}></Icon>
