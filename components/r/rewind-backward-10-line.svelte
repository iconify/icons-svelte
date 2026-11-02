<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2g41okh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz2g41okh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-10-line" {...props}></Icon>
