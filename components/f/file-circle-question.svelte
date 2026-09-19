<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4c39fp6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="a4c39fp6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-circle-question" {...props}></Icon>
