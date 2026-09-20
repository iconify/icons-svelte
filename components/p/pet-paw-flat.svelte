<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7izu_bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n7izu_bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:pet-paw-flat" {...props}></Icon>
