<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_zinnm-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="u_zinnm-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:minus" {...props}></Icon>
