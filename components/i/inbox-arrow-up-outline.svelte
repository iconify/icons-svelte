<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc1h2ybiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1h2ybiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:inbox-arrow-up-outline" {...props}></Icon>
