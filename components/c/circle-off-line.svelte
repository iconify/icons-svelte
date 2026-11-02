<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsl-0tizg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsl-0tizg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-off-line" {...props}></Icon>
