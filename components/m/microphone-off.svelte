<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff0bb0b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff0bb0b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:microphone-off" {...props}></Icon>
