<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpun400or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":633};
const content = `<path class="mpun400or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bing" {...props}></Icon>
