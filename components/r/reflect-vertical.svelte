<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihekl3wxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihekl3wxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:reflect-vertical" {...props}></Icon>
