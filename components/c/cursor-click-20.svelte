<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2qxyibcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2qxyibcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-click-20" {...props}></Icon>
