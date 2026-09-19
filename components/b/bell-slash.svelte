<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jda6pyvez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jda6pyvez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bell-slash" {...props}></Icon>
