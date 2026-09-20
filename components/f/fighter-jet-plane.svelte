<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7uswhbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y7uswhbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fighter-jet-plane" {...props}></Icon>
