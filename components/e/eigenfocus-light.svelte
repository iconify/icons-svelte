<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa3r_abyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aa3r_abyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eigenfocus-light" {...props}></Icon>
