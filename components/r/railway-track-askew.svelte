<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d254ld3ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d254ld3ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:railway-track-askew" {...props}></Icon>
