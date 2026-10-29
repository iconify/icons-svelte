<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdg-icb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdg-icb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-y" {...props}></Icon>
