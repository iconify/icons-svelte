<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkyvgqa0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkyvgqa0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-inflight-fill" {...props}></Icon>
