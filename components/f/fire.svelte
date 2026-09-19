<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0lrd7bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="e0lrd7bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:fire" {...props}></Icon>
