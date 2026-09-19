<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgg_xqblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xgg_xqblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:play-alt" {...props}></Icon>
