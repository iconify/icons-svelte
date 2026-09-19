<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5w009yic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5w009yic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gyroscope" {...props}></Icon>
