<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7r-vt5ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7r-vt5ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hospital-building-pin-bold" {...props}></Icon>
