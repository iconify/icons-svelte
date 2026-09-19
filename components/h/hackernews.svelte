<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1ovebts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gr1ovebts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:hackernews" {...props}></Icon>
