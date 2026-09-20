<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy1ra6i_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jy1ra6i_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-top-left-bottom-right" {...props}></Icon>
