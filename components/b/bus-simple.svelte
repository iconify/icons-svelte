<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0fis8b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b0fis8b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bus-simple" {...props}></Icon>
