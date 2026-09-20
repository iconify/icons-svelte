<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-g22cfbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="e-g22cfbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:megaphone-1" {...props}></Icon>
