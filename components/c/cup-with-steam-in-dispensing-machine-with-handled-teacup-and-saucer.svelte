<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vztls8b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vztls8b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cup-with-steam-in-dispensing-machine-with-handled-teacup-and-saucer" {...props}></Icon>
