<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8cnbcap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gp8cnbcap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hands-bound" {...props}></Icon>
