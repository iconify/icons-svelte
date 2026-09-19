<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/balawacqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="balawacqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bars-staggered" {...props}></Icon>
