<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trmo9wb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="trmo9wb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:drafting-compass" {...props}></Icon>
