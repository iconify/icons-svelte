<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap8ol18hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap8ol18hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heater" {...props}></Icon>
