<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0c2khzel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h0c2khzel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plane-circle-check" {...props}></Icon>
