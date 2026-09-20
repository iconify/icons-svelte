<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkvla1b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkvla1b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:airplane-mode" {...props}></Icon>
