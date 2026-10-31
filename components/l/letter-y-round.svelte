<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sze-jacfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sze-jacfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-y-round" {...props}></Icon>
