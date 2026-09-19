<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad7p1c9ad.css';
import '../../css/e/e32x_9b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ad7p1c9ad"/><path class="e32x_9b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:meteor-wordmark" {...props}></Icon>
