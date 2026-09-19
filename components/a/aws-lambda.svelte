<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wub6bgheq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wub6bgheq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:aws-lambda" {...props}></Icon>
