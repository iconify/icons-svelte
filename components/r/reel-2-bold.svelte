<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf3nmubio.css';
import '../../css/t/tjfdtw4pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3nmubio"/><path clip-rule="evenodd" class="tjfdtw4pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reel-2-bold" {...props}></Icon>
