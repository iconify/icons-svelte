<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yprrdym3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yprrdym3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-recycling-symbol" {...props}></Icon>
