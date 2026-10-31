<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkjb51frr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkjb51frr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gauge-round" {...props}></Icon>
