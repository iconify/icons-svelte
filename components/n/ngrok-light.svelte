<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wct01yjnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":92.11};
const content = `<path class="wct01yjnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ngrok-light" {...props}></Icon>
