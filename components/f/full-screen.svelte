<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc9zikbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tc9zikbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:full-screen" {...props}></Icon>
