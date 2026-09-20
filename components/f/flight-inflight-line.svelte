<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i31rusxkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i31rusxkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-inflight-line" {...props}></Icon>
