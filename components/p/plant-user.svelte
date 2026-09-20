<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vli6zsotx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vli6zsotx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-user" {...props}></Icon>
