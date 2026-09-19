<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj7tdsdto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cj7tdsdto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:broom" {...props}></Icon>
