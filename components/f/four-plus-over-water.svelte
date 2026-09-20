<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywgza-9bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ywgza-9bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-plus-over-water" {...props}></Icon>
