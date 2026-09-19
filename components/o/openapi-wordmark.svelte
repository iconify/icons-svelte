<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic_-zr8ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ic_-zr8ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:openapi-wordmark" {...props}></Icon>
