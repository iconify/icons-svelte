<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjjbb0bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjjbb0bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-6-thin" {...props}></Icon>
