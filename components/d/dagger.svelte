<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8mohmb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u8mohmb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dagger" {...props}></Icon>
