<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvdl-nkot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jvdl-nkot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grip-lines-vertical" {...props}></Icon>
