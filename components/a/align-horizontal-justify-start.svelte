<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8pqt-3zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8pqt-3zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-justify-start" {...props}></Icon>
