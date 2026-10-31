<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts83b_9vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts83b_9vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fold-horizontal-fill-round" {...props}></Icon>
