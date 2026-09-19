<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-bl3vbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-bl3vbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:erase" {...props}></Icon>
