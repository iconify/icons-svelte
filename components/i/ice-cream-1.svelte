<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0uk58atx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0uk58atx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ice-cream-1" {...props}></Icon>
