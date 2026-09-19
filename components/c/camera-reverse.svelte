<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgoy5g6-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgoy5g6-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:camera-reverse" {...props}></Icon>
