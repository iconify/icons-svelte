<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rss1k6blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rss1k6blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fuga-cloud" {...props}></Icon>
