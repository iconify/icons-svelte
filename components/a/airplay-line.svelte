<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5k9mk7lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5k9mk7lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:airplay-line" {...props}></Icon>
