<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msf02b-ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="msf02b-ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:flickr" {...props}></Icon>
