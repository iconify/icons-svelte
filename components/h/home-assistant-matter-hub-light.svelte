<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufun8cc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufun8cc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-assistant-matter-hub-light" {...props}></Icon>
