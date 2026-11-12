<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7o6x_2pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7o6x_2pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotify-dark" {...props}></Icon>
