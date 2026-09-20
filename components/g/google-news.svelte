<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj9tx7bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj9tx7bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-news" {...props}></Icon>
