<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_mj2m24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z_mj2m24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-link" {...props}></Icon>
