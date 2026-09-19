<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk-q5i3tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gk-q5i3tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:magento-wordmark" {...props}></Icon>
