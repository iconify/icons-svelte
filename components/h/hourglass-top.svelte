<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfcca5big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfcca5big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hourglass-top" {...props}></Icon>
