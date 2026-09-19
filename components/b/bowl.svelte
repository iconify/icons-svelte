<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d55dnvb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d55dnvb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:bowl" {...props}></Icon>
