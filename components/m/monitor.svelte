<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7g2f1bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7g2f1bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:monitor" {...props}></Icon>
