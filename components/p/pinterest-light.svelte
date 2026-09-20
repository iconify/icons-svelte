<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f43t98_ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f43t98_ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinterest-light" {...props}></Icon>
