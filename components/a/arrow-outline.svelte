<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5jusru4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w5jusru4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-outline" {...props}></Icon>
