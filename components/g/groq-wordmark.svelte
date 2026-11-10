<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnva4_vbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hnva4_vbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:groq-wordmark" {...props}></Icon>
