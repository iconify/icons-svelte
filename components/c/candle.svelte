<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkh_dk9bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkh_dk9bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:candle" {...props}></Icon>
