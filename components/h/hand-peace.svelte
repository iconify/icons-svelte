<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjhyvcc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jjhyvcc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-peace" {...props}></Icon>
