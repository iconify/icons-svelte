<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4-p-yb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4-p-yb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hacker-news-dark" {...props}></Icon>
