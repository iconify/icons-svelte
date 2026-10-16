<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8xo_c6fy.css';
import '../../css/k/kwq58xm-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g8xo_c6fy"/><path class="kwq58xm-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-reel-20-bold" {...props}></Icon>
