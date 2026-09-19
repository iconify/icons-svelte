<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baxcrzb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baxcrzb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ai-assistant-filled" {...props}></Icon>
