<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0b9b_y4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0b9b_y4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:a-cane" {...props}></Icon>
