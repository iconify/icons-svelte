<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvss-gzwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvss-gzwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-triple-right" {...props}></Icon>
