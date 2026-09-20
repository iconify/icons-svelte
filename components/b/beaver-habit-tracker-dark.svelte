<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2f-szb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2f-szb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beaver-habit-tracker-dark" {...props}></Icon>
