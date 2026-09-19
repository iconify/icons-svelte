<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abz4jnh1h.css';
import '../../css/f/f_bgirb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="abz4jnh1h"/><path class="f_bgirb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-company-filled" {...props}></Icon>
