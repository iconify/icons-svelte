<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toyuwsb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="toyuwsb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dzone" {...props}></Icon>
