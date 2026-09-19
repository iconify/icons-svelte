<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqu-xr9bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jqu-xr9bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:frown-o" {...props}></Icon>
