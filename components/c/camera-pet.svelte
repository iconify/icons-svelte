<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8wyu3a9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wyu3a9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:camera-pet" {...props}></Icon>
