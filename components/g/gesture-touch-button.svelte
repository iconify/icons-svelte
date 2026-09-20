<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk_2ytb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_2ytb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gesture-touch-button" {...props}></Icon>
