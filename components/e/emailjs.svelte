<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upn1q9b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="upn1q9b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:emailjs" {...props}></Icon>
