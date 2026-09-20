<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbo9cf8pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbo9cf8pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-pyramid-fill" {...props}></Icon>
