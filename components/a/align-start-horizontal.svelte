<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpi7ur37t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpi7ur37t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-start-horizontal" {...props}></Icon>
