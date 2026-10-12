<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2hel0pen.css';
import '../../css/b/b5hazkbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2hel0pen"/><path class="b5hazkbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-chip-20-bold" {...props}></Icon>
