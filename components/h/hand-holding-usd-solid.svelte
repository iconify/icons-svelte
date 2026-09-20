<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldxv6tbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ldxv6tbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-holding-usd-solid" {...props}></Icon>
