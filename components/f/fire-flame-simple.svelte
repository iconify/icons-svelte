<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg34ccc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fg34ccc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fire-flame-simple" {...props}></Icon>
