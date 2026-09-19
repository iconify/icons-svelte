<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4gg6fwiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j4gg6fwiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:foursquare" {...props}></Icon>
