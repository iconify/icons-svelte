<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj9jajbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mj9jajbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:hacker-news" {...props}></Icon>
