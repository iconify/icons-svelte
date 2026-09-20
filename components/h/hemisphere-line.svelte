<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pigl6sbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pigl6sbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-line" {...props}></Icon>
