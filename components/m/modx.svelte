<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv4b9k1_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hv4b9k1_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:modx" {...props}></Icon>
