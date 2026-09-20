<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n20_8lkzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n20_8lkzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:land-plots-marker" {...props}></Icon>
