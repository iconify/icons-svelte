<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydv6ohbun.css';
import '../../css/g/g-mfsnbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ydv6ohbun"/><path class="g-mfsnbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:discloud-wordmark" {...props}></Icon>
