<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue30s2b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ue30s2b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pocketbase-wordmark" {...props}></Icon>
