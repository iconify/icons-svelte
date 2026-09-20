<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl8h2wwbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl8h2wwbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-space-between" {...props}></Icon>
