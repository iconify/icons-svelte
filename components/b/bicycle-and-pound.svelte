<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brwgglt3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="brwgglt3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-pound" {...props}></Icon>
