<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1n0r_6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cu1n0r_6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:blog" {...props}></Icon>
