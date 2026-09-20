<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5oq8rb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="r5oq8rb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bus-stop-10" {...props}></Icon>
