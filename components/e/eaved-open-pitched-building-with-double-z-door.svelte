<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2y9x-b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f2y9x-b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-open-pitched-building-with-double-z-door" {...props}></Icon>
