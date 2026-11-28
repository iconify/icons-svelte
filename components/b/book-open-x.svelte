<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkgugcbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkgugcbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-open-x" {...props}></Icon>
