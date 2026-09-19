<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp4b02vui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gp4b02vui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-012" {...props}></Icon>
