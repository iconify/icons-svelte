<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkvfwp7eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="rkvfwp7eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mobile-screen" {...props}></Icon>
