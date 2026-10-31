<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn9grkqjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn9grkqjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-off-fill-round" {...props}></Icon>
