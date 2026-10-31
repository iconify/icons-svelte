<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dia1yf76r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dia1yf76r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-check-fill-round" {...props}></Icon>
