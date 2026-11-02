<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce2w5xbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce2w5xbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-left-line" {...props}></Icon>
