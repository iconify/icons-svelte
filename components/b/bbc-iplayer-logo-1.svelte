<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaov8kxvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaov8kxvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bbc-iplayer-logo-1" {...props}></Icon>
