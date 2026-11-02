<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suxrgxbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suxrgxbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dinner-line" {...props}></Icon>
