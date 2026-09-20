<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9-_fxbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k9-_fxbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:anticlockwise-90-outline" {...props}></Icon>
