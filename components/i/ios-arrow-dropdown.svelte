<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv3w-bboh.css';
import '../../css/e/e0us24bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv3w-bboh"/><path class="e0us24bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropdown" {...props}></Icon>
