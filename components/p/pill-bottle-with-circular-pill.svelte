<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm4zygbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dm4zygbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pill-bottle-with-circular-pill" {...props}></Icon>
