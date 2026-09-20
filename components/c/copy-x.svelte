<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2f1anxyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2f1anxyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:copy-x" {...props}></Icon>
