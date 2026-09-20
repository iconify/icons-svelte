<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-7s0mshg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z-7s0mshg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:folder-check" {...props}></Icon>
