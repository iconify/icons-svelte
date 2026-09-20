<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc-kidcwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fc-kidcwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five-one-one" {...props}></Icon>
