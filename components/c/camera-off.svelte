<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwg23r9ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwg23r9ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:camera-off" {...props}></Icon>
