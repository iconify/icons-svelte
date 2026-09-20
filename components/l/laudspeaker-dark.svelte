<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsw6ydedy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hsw6ydedy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:laudspeaker-dark" {...props}></Icon>
