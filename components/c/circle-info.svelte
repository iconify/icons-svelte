<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkmn9bbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkmn9bbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:circle-info" {...props}></Icon>
