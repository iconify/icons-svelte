<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_6syhbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r_6syhbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-rupee" {...props}></Icon>
