<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_zlrubeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h_zlrubeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-right" {...props}></Icon>
