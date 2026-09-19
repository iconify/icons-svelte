<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_1rp79vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e_1rp79vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:eclipse-wordmark" {...props}></Icon>
