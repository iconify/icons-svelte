<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vugj7860w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vugj7860w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picture-off-outline" {...props}></Icon>
