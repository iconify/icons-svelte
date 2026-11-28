<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej8fvvbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej8fvvbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bot-play" {...props}></Icon>
