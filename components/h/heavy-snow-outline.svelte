<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzxn7xbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bzxn7xbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:heavy-snow-outline" {...props}></Icon>
