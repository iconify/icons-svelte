<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg8g3kb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg8g3kb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-round" {...props}></Icon>
