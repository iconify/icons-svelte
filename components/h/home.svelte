<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7nlnb-_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7nlnb-_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:home" {...props}></Icon>
