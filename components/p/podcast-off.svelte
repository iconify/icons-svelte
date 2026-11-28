<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh9dy1eza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh9dy1eza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast-off" {...props}></Icon>
