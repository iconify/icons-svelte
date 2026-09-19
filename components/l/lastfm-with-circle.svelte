<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgwktoj5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lgwktoj5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:lastfm-with-circle" {...props}></Icon>
