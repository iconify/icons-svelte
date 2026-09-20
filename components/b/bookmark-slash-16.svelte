<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0h--2odr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0h--2odr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-slash-16" {...props}></Icon>
