<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egh4vqbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egh4vqbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heart-pulse-check" {...props}></Icon>
