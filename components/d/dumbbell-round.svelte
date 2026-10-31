<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd8w5db4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd8w5db4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dumbbell-round" {...props}></Icon>
