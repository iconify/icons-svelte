<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3mopsuqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="x3mopsuqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-616" {...props}></Icon>
