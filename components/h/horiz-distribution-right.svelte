<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcr6e9rss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcr6e9rss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:horiz-distribution-right" {...props}></Icon>
