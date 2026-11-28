<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad5u6q4jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad5u6q4jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bookmark-plus" {...props}></Icon>
