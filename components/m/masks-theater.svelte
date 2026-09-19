<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe4f2nbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fe4f2nbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:masks-theater" {...props}></Icon>
