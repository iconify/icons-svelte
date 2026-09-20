<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh3wbdc-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sh3wbdc-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rocketship" {...props}></Icon>
