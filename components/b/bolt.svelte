<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jalbr5rjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jalbr5rjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bolt" {...props}></Icon>
