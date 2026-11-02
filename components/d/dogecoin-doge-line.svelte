<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e10ivmb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e10ivmb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dogecoin-doge-line" {...props}></Icon>
