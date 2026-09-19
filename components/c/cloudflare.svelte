<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_bz9ul3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_bz9ul3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cloudflare" {...props}></Icon>
