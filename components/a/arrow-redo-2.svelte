<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seli0bcod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seli0bcod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-redo-2" {...props}></Icon>
