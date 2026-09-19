<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqraoh7pn.css';
import '../../css/a/a7w15ebva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rqraoh7pn"/><path class="a7w15ebva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:emailjs-wordmark" {...props}></Icon>
