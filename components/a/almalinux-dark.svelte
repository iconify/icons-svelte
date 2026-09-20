<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3x_g1b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3x_g1b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:almalinux-dark" {...props}></Icon>
