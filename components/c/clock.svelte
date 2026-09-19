<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyu5r4bdv.css';
import '../../css/g/gwp8_q19n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu5r4bdv"/><path class="gwp8_q19n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock" {...props}></Icon>
