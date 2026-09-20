<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0csv9xci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0csv9xci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-check-outline" {...props}></Icon>
