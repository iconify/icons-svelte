<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iowo5oevp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iowo5oevp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rancher-wordmark" {...props}></Icon>
