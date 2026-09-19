<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_8v8gnuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h_8v8gnuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:facebook" {...props}></Icon>
