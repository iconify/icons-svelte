<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tznxr9bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tznxr9bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:laptop-file" {...props}></Icon>
