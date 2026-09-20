<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9lrubca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zc9lrubca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pedestrian-walled" {...props}></Icon>
