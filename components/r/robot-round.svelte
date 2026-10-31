<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dje5wsi9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dje5wsi9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:robot-round" {...props}></Icon>
