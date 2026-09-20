<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh8bykbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wh8bykbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray" {...props}></Icon>
