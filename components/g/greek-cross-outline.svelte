<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5hdy8lkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h5hdy8lkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:greek-cross-outline" {...props}></Icon>
