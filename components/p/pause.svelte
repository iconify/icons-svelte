<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbfp1yoag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rbfp1yoag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pause" {...props}></Icon>
