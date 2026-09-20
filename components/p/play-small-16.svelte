<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkhl2obdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pkhl2obdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:play-small-16" {...props}></Icon>
