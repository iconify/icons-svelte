<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvs2kr1fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvs2kr1fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flip-vertical-round" {...props}></Icon>
