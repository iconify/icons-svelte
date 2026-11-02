<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guipbacim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guipbacim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-down-line" {...props}></Icon>
