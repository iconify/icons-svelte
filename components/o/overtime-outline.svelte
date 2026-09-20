<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwi7mvckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwi7mvckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:overtime-outline" {...props}></Icon>
