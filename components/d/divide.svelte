<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ab8ca9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p5ab8ca9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:divide" {...props}></Icon>
