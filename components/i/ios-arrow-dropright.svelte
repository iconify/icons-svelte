<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odyie6but.css';
import '../../css/e/en-3d656m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odyie6but"/><path class="en-3d656m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropright" {...props}></Icon>
