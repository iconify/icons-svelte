<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4-2ht45e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h4-2ht45e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:leetcode-wordmark" {...props}></Icon>
