<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cthmeyb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cthmeyb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-front-fill" {...props}></Icon>
