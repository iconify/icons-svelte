<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkvaydyvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvaydyvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:langflow" {...props}></Icon>
