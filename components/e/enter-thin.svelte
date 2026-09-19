<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fii_z8bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fii_z8bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:enter-thin" {...props}></Icon>
