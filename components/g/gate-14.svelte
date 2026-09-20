<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za6dc3b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="za6dc3b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:gate-14" {...props}></Icon>
