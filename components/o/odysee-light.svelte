<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7k3x5q8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7k3x5q8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:odysee-light" {...props}></Icon>
