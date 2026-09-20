<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsll_2ggj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsll_2ggj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-magnify" {...props}></Icon>
