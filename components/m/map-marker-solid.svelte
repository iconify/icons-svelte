<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc9m02b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lc9m02b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-marker-solid" {...props}></Icon>
