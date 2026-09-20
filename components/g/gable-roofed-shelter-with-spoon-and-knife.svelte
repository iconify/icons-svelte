<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_mpl-t0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_mpl-t0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gable-roofed-shelter-with-spoon-and-knife" {...props}></Icon>
