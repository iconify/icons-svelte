<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f58oytbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f58oytbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:hacker-news-square" {...props}></Icon>
