<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0mblbcim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0mblbcim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-cny-fill" {...props}></Icon>
