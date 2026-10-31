<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdop1ebcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdop1ebcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bulb-sparkle-round" {...props}></Icon>
