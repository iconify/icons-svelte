<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixv82_hid.css';
import '../../css/e/e6-p1ybyd.css';
import '../../css/b/bxy1g4b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ixv82_hid"/><path class="e6-p1ybyd"/><path class="bxy1g4b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-one-20-bold" {...props}></Icon>
