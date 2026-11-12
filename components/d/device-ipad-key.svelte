<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i94675ujg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i94675ujg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-key" {...props}></Icon>
