<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5k65pgym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5k65pgym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bludit-dark" {...props}></Icon>
