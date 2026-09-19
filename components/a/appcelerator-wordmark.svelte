<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxhbwqfms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cxhbwqfms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:appcelerator-wordmark" {...props}></Icon>
