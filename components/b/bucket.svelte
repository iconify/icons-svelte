<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgl2qg0kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xgl2qg0kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bucket" {...props}></Icon>
