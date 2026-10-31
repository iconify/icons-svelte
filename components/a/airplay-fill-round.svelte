<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bym8_6bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bym8_6bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:airplay-fill-round" {...props}></Icon>
