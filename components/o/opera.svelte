<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvb64fcio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvb64fcio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:opera" {...props}></Icon>
