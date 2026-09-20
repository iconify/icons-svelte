<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5-gh6bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f5-gh6bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:0-above-water" {...props}></Icon>
