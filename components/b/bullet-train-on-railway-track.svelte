<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sokfneber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sokfneber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bullet-train-on-railway-track" {...props}></Icon>
