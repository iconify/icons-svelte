<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgzirsm5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgzirsm5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:libra-line" {...props}></Icon>
