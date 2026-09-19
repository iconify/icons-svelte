<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swxpzcv9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swxpzcv9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:orcid" {...props}></Icon>
