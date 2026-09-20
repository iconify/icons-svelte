<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8dmtfb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w8dmtfb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:consume-filled" {...props}></Icon>
