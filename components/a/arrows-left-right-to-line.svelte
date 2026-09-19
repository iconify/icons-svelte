<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io8cndj1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="io8cndj1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-left-right-to-line" {...props}></Icon>
