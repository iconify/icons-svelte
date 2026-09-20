<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtm3f6bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wtm3f6bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:dam" {...props}></Icon>
