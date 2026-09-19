<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usi9ys8jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":476,"height":512};
const content = `<path class="usi9ys8jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:asymptote-alt" {...props}></Icon>
