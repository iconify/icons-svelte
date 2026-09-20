<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiexllbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiexllbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:audio-input-xlr" {...props}></Icon>
