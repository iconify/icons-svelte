<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j57b6uxil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j57b6uxil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:level-down" {...props}></Icon>
