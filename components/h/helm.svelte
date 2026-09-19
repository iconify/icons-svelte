<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmwadnbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jmwadnbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:helm" {...props}></Icon>
