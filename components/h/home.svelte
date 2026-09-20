<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h32an4f6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h32an4f6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:home" {...props}></Icon>
