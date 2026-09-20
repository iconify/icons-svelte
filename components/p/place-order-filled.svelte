<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nezot8bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nezot8bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:place-order-filled" {...props}></Icon>
