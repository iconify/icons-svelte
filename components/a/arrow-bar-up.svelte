<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbv05ubbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbv05ubbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-bar-up" {...props}></Icon>
