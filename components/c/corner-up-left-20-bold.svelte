<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs5ldor7z.css';
import '../../css/i/ins2hsbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cs5ldor7z"/><path class="ins2hsbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-left-20-bold" {...props}></Icon>
