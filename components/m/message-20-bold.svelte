<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-vg6lr_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-vg6lr_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-20-bold" {...props}></Icon>
