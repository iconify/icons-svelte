<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmhc97bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmhc97bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:book-content" {...props}></Icon>
