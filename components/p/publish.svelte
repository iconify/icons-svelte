<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r650umq3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r650umq3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:publish" {...props}></Icon>
