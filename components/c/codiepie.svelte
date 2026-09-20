<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6tvidf3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6tvidf3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:codiepie" {...props}></Icon>
