<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lngqecb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="lngqecb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hacker-news" {...props}></Icon>
