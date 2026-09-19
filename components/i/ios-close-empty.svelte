<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myg5r-y-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="myg5r-y-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-close-empty" {...props}></Icon>
