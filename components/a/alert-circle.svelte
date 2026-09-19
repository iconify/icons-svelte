<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mica3mhlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="mica3mhlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alert-circle" {...props}></Icon>
