<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpvptsbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fpvptsbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cog-8-tooth-16-solid" {...props}></Icon>
