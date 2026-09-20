<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_98zbbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_98zbbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico-dark" {...props}></Icon>
