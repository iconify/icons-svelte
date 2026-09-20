<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbc-0cpda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbc-0cpda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d4" {...props}></Icon>
