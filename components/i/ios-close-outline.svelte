<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg35tlbum.css';
import '../../css/a/at_92mbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yg35tlbum"/><path class="at_92mbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-close-outline" {...props}></Icon>
