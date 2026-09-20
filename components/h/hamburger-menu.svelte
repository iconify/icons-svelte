<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0elk-azn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k0elk-azn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hamburger-menu" {...props}></Icon>
