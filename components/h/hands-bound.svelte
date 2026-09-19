<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v5rqj_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c9v5rqj_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hands-bound" {...props}></Icon>
