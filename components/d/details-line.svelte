<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9snz0bpr.css';
import '../../css/z/zmn89rczy.css';
import '../../css/i/igyet2bst.css';
import '../../css/a/aulpu3kwr.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 p9snz0bpr"/><path class="clr-i-outline clr-i-outline-path-2 zmn89rczy"/><path class="clr-i-outline clr-i-outline-path-3 igyet2bst"/><path class="aulpu3kwr clr-i-outline clr-i-outline-path-4"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:details-line" {...props}></Icon>
