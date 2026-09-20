<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyv60mbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyv60mbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ngrok" {...props}></Icon>
