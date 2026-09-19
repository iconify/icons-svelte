<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-764axmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-764axmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:download" {...props}></Icon>
