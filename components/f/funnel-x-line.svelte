<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzicabcvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzicabcvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:funnel-x-line" {...props}></Icon>
