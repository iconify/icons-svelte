<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3v08dgfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f3v08dgfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-outline" {...props}></Icon>
