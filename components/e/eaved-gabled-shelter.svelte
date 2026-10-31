<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il5s5zklx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="il5s5zklx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-shelter" {...props}></Icon>
