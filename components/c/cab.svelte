<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5wzjsfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og5wzjsfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cab" {...props}></Icon>
