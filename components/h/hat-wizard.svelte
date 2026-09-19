<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djefxr29r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djefxr29r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hat-wizard" {...props}></Icon>
