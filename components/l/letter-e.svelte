<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd31yq_fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd31yq_fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-e" {...props}></Icon>
