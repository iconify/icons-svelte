<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an-ar2bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an-ar2bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-start-vertical" {...props}></Icon>
