<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trzqa8bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trzqa8bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moodist-dark" {...props}></Icon>
