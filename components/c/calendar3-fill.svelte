<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3q8_p7qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i3q8_p7qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar3-fill" {...props}></Icon>
