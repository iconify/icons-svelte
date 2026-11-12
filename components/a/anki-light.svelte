<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7h-q9q4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7h-q9q4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anki-light" {...props}></Icon>
