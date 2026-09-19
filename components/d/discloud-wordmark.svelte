<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4cxb1bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l4cxb1bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:discloud-wordmark" {...props}></Icon>
