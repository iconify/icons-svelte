<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3r4d62pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3r4d62pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arch-linux-dark" {...props}></Icon>
