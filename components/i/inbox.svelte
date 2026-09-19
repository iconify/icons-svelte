<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybu9p90zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ybu9p90zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:inbox" {...props}></Icon>
