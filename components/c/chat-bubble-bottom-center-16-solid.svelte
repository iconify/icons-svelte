<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftqjed4ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ftqjed4ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center-16-solid" {...props}></Icon>
