<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wourn01uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wourn01uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:lighthouse-15" {...props}></Icon>
