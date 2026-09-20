<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzh0n7bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vzh0n7bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-house-with-chimney" {...props}></Icon>
