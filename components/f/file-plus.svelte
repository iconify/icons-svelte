<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acyvj8jmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acyvj8jmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:file-plus" {...props}></Icon>
