<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fikfu_54f.css';
import '../../css/e/ec43nwb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="fikfu_54f"/><path class="ec43nwb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:launchpad-line" {...props}></Icon>
