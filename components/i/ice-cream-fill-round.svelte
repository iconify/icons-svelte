<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_w7_5kaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_w7_5kaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ice-cream-fill-round" {...props}></Icon>
