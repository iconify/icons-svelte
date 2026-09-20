<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azgrjsb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="azgrjsb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico-sh-dark" {...props}></Icon>
