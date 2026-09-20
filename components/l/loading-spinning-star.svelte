<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md78e4_pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md78e4_pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:loading-spinning-star" {...props}></Icon>
