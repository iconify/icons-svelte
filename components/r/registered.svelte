<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3cgxdb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m3cgxdb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:registered" {...props}></Icon>
